<template>
  <div class="user-info">
    <h2>Thông tin cá nhân</h2>
    <ul>
      <li>Họ và tên: <strong>{{ user.fullName }}</strong></li>
      <li>Giới tính: {{ user.gender }}</li>
      <li>Ngày sinh: {{ user.dob }}</li>
      <li>Email: {{ user.email }}</li>
      <li>Địa chỉ: {{ user.address }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      user: {
        fullName: "Nguyễn Văn A",
        gender: "Nam",
        dob: "06/03/2024",
        email: "nva@gmail.com",
        address: "Thanh Xuân, Hà Nội"
      }
    };
  }
};
</script>

<style scoped>
.user-info {
  border: 1px solid #ccc;
  padding: 20px;
  border-radius: 10px;
  width: 300px;
  font-family: Arial, sans-serif;
}

.user-info h2 {
  text-align: center;
}

.user-info ul {
  list-style-type: none;
  padding: 0;
}

.user-info li {
  margin-bottom: 10px;
}

strong {
  font-weight: bold;
}
</style>

<template>
  <div class="user-name">
    <p>Họ và tên: <strong>{{ formatName(user) }}</strong></p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      user: {
        firstName: "Nguyễn Thanh",
        lastName: "Tùng"
      }
    };
  },
  methods: {
    formatName(user) {
      return `${user.firstName} ${user.lastName}`;
    }
  }
};
</script>

<style scoped>
.user-name {
  font-family: Arial, sans-serif;
  font-size: 18px;
  margin: 20px;
}

strong {
  font-weight: bold;
}
</style>

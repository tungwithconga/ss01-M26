<template>
  <div>
    <input type="number" id="num1" placeholder="Enter first number">
    <input type="number" id="num2" placeholder="Enter second number">
    
    <button onclick="calculate('+')">Cộng</button>
    <button onclick="calculate('-')">Trừ</button>
    <button onclick="calculate('*')">Nhân</button>
    <button onclick="calculate('/')">Chia</button>

    <p id="result">Kết quả: </p>
    </div>
</template>

<script>
        function add(a, b) {
            return a + b;
        }

        function subtract(a, b) {
            return a - b;
        }

        function multiply(a, b) {
            return a * b;
        }

        function divide(a, b) {
            if (b === 0) {
                return "Không thể chia cho 0";
            }
            return a / b;
        }

        function calculate(operation) {
            const num1 = parseFloat(document.getElementById('num1').value);
            const num2 = parseFloat(document.getElementById('num2').value);
            let result;

            if (isNaN(num1) || isNaN(num2)) {
                result = "Vui lòng nhập số hợp lệ.";
            } else {
                switch (operation) {
                    case '+':
                        result = add(num1, num2);
                        break;
                    case '-':
                        result = subtract(num1, num2);
                        break;
                    case '*':
                        result = multiply(num1, num2);
                        break;
                    case '/':
                        result = divide(num1, num2);
                        break;
                }
            }

            document.getElementById('result').textContent = `Kết quả: ${result}`;
        }
</script>

<style>

</style>
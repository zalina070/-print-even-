# -print-even-
function printEvenNumbers() {
  for (let i = 0; i <= 100; i++) {
    if (i % 2 === 0) {
      console.log(i);
    }
  }
}

# -print-odd-
function printOddNumbers() {
  for (let i = 100; i >= 0; i--) {
    if (i % 2 !== 0) {
      console.log(i);
    }
  }
}

// Пример вызова
printEvenNumbers();
printOddNumbers();

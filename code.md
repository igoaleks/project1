const data = [1, 0, 2, 0, 3, 0, 4, 0, 5]
const result = data.sort((a,b) => !a ? -1 : (!b ? 1 : b - a))
console.log(result)

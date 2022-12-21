# 두 수의 나눗셈
#### 문제 설명 : 정수 num1과 num2가 매개변수로 주어질 때, num1을 num2로 나눈 값에 1,000을 곱한 후 정수 부분을 return 하도록 soltuion 함수를 완성해주세요.
```
function solution(num1, num2) {
    let answer = Math.floor((num1 / num2) * 1000);
    return answer;
}
```
# 짝수의 합
#### 문제 설명 : 정수 n이 주어질 때, n이하의 짝수를 모두 더한 값을 return 하도록 solution 함수를 작성해주세요.
```
function solution(n) {
    let answer = 0;
    for (let i = 0; i <= n; i++) {
        if (i % 2 === 0)
        answer += i
    }
    return answer;
}
```
# 배열의 평균값
#### 문제 설명 : 정수 배열 numbers가 매개변수로 주어집니다. numbers의 원소의 평균값을 return하도록 solution 함수를 완성해주세요.
```
function solution(numbers) {
    let answer = 0;
    for (let i = 0; i < numbers.length; i++) {
        answer += numbers[i] / numbers.length
    }
    return answer;
}
```
# 양꼬치
#### 문제 설명 : 머쓱이네 양꼬치 가게는 10인분을 먹으면 음료수 하나를 서비스로 줍니다. 양꼬치는 1인분에 12,000원, 음료수는 2,000원입니다. 정수 n과 k가 매개변수로 주어졌을 때, 양꼬치 n인분과 음료수 k개를 먹었다면 총얼마를 지불해야 하는지 return 하도록 solution 함수를 완성해보세요.
```

```

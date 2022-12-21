# 나이 출력
#### 문제 설명 : 머쓱이는 40살인 선생님이 몇 년도에 태어났는지 궁금해졌습니다. 나이 age가 주어질 때, 2022년을 기준 출생 연도를 return 하는 solution 함수를 완성해주세요.
```
function solution(age) {
    let answer = 2023 - age;
    return answer;
}
```
# 두 수의 합
#### 문제 설명 : 정수 num1과 num2가 주어질 때, num1과 num2의 합을 return하도록 soltuion 함수를 완성해주세요.
```
function solution(num1, num2) {
    let answer = num1 + num2;
    return answer;
}
```
# 숫자 비교하기
#### 문제 설명 : 정수 num1과 num2가 매개변수로 주어집니다. 두 수가 같으면 1 다르면 -1을 retrun하도록 solution 함수를 완성해주세요.
```
function solution(num1, num2) {
    if (num1 === num2) {
        return 1
    } else {
        return -1
    }
}
```
# 각도기
#### 문제 설명 : 각에서 0도 초과 90도 미만은 예각, 90도는 직각, 90도 초과 180도 미만은 둔각 180도는 평각으로 분류합니다. 각 angle이 매개변수로 주어질 때 예각일 때 1, 직각일 때 2, 둔각일 때 3, 평각일 때 4를 return하도록 solution 함수를 완성해주세요.
```
function solution(angle) {
    if (0 < angle && angle < 90) {
        return 1
    } else if (angle === 90) {
        return 2
    } else if (90 < angle && angle < 180) {
        return 3
    } else (angle === 180)
        return 4
}
``` 

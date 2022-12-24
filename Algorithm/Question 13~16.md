# 머쓱이보다 키 큰 사람
#### 문제 설명 : 머쓱이는 학교에서 키 순으로 줄을 설 때 몇 번째로 서야 하는지 궁금해졌습니다. 머쓱이네 반 친구들의 키가 담긴 정수 배열 array와 머쓱이의 키 height가 매개변수로 주어질 때, 머쓱이보다 키 큰 사람 수를 return 하도록 solution 함수를 완성해보세요.
```
function solution(array, height) {
    let answer = 0;
    for (let i = 0; i < array.length; i++) {
        if (array[i] > height) {
            answer++
        }
    }
    return answer;
}
```
# 중복된 숫자 개수
#### 문제 설명 : 정수가 담긴 배열 array와 정수 n이 매개변수로 주어질 때, array에 n이 몇 개 있는 지를 return 하도록 solution 함수를 완성해보세요.
```

```
# 배열 뒤집기
#### 문제 설명 : 정수가 들어 있는 배열 num_list가 매개변수로 주어집니다. num_list의 원소의 순서를 거꾸로 뒤집은 배열을 return하도록 solution 함수를 완성해주세요.
```
function solution(num_list) {
    const answer = num_list.reverse()
    return answer;
}
```
# 배열 두배 만들기
#### 문제 설명 : 정수 배열 numbers가 매개변수로 주어집니다. numbers의 각 원소에 두배한 원소를 가진 배열을 return하도록 solution 함수를 완성해주세요.
```
function solution(numbers) {
    return numbers.map((a) => a*2)
}
```

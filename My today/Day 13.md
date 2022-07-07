# 7월 07일 목요일

## JS 예제 풀어보기 
지난주부터 계속 고민했지만 해결하지 못한 등급만들기!!! 

드디어 새벽에 해냈다. 

비록 오래 걸렸지만,,, 풀고나서 보니까 점표기법으로 차근차근 풀어낸 것 같았다. 

그리고 if 문에서 ? 점 이상 ? 점 미만을 만드는 과정에서 코드를 잘못 작성했다. 

사실 왜 그 전꺼는 undefined가 나오고 &&로 작성한 코드는 결과값이 출력되는지 원인을 몰라서 내일 스터디때 물어보려한다. 

내가 풀어낸 코드!! 
```JavaScript
// 정보
const Attendance = [
  { name:"유신", korScore:92, enScore : 79, mathScore : 68 },
  { name:"세화", korScore:70, enScore : 83, mathScore : 90 },
  { name:"경태", korScore:87, enScore : 85, mathScore : 87 },
  { name:"지웅", korScore:77, enScore : 87, mathScore : 99 },
  { name:"예찬", korScore:90, enScore : 80, mathScore : 65 }
];

// 등급 만드는 코드
function printGrade(Score) {
  let final=null;

  if (Score < 60) {
    return 'D';
  } else if (Score >= 60 && Score < 75) {
    return 'C';
  } else if (Score >= 75 && Score < 90) {
    return 'B';
  } else if (Score >= 90) {
    return 'A';
  }
}; 

// 이름, 국어 점수, 등급 출력 코드
console.log('이름 : ' + Attendance[0].name, '국어점수 : ' + Attendance[0].korScore, '등급 : ' +  printGrade(Attendance[0].korScore))
console.log('이름 : ' + Attendance[1].name, '국어점수 : ' + Attendance[1].korScore, '등급 : ' +  printGrade(Attendance[1].korScore))
console.log('이름 : ' + Attendance[2].name, '국어점수 : ' + Attendance[2].korScore, '등급 : ' +  printGrade(Attendance[2].korScore))
console.log('이름 : ' + Attendance[3].name, '국어점수 : ' + Attendance[3].korScore, '등급 : ' +  printGrade(Attendance[3].korScore))
console.log('이름 : ' + Attendance[4].name, '국어점수 : ' + Attendance[4].korScore, '등급 : ' +  printGrade(Attendance[4].korScore))
```
![image](https://user-images.githubusercontent.com/100126319/177801824-5b6e82d5-08f2-410d-aa78-9ce7d98df5bd.png)

## 멘토링 
### 준비
- 회사 찾아보기
- 내용 정리하기 

### 참여
면접에서 이런 질문을 받는다면 어떻게 답변할 것 같아요?

오늘 멘토링에 참여하며 30분 내내 소름이 돋았다... 

멘토님과 답변을 해보는 과정에서 '아직 내가 사회복지 시절을 깨부수지 못했구나.'라는 생각이 정말 많이 들었다. 

사회복지는 보수적인 집단이다. 

질문에 대한 답변을 할 때 굉장히 조심스럽고 약간의 답정너..? 같은 느낌이 있다. 

오늘 멘토님 덕분에 내 생각을 솔직하게 정리해서 답변할 수 있도록 내 마음을 정리해봐야겠다고 생각했다. 

### 오늘 하루 유레카!!

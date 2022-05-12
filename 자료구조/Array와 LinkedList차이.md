#### Array와 LinkedList차이점
<br>
<br>
<table>
  <tr>
    <th>구분</th>
    <th>Array</th>
    <th>LinkedList</th>
  </tr>
  <tr>
    <td><b>검색</b></td>
    <td>데이터에 <b>직접</b> 접근하므로 읽기/쓰기가 연결리스트에 비해 빠름</td>
    <td>데이터에 <b>순차</b> 접근해야 하므로 읽기/쓰기가 배열에 비해 느림</td>
  </tr>
  <tr>
    <td><b>데이터/구조 변경</b></td>
    <td>추가/삭제 시 반복 이동이 필요함</td>
    <td>노드 추가/삭제 용이</td>
  </tr>
    <tr>
    <td><b>기억 공간</b></td>
    <td>코딩시 정해진 크기만큼 정적할당</td>
    <td>노드 필요시 동적할당하여 연결함</td>
  </tr>
    <tr>
    <td><b>추가 기억 공간</b></td>
    <td>링크 필드 추가</td>
    <td> 추가/삭제 시 반복 이동이 필요함</td>
  </tr>
    <tr>
    <td><b>소멸</b></td>
    <td>배열은 함수 종료 때 전역 배열은 프로그램 종료 때</td>
    <td>매 노드마다 free() 함수를 사용</td>
  </tr>
</table>

<br>
<br>
<br>

- Array : index로 접근 후 삽입 및 삭제
- LinkedList : 삽입하려는 위치 접근 후 삽입 및 삭제
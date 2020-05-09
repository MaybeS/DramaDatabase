# Drama Database

Includes columns below:
```
방송 기간, 방송 횟수, 장르, 채널, 제작사, 극본, 출연자
```

## Dataframe from Wiki dump

### Wekipedia

See also `labs/wikipedia.ipynb` and put dump file to `data/kowiki.xml`.

### Namuwiki

See also `labs/namuwiki.ipynb` and put dump file to `data/namuwiki.json`.

## Dataframe
Dataframe`results/results.csv`. 
shape: 1912 &times; 9

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>제목</th>
      <th>방송 기간</th>
      <th>방송 횟수</th>
      <th>장르</th>
      <th>채널</th>
      <th>제작사</th>
      <th>극본</th>
      <th>출연자</th>
      <th>방송 시작</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>외과의사봉달희</td>
      <td>2007년 1월 17일 ~ 2007년 3월 15일</td>
      <td>18부작</td>
      <td>의학 드라마</td>
      <td>SBS TV</td>
      <td>DSP 미디어</td>
      <td>[[이정선 (작가)</td>
      <td>이요원, 이범수, 김민준, 오윤아 외</td>
      <td>2007-01-17 00:00:00</td>
    </tr>
    <tr>
      <th>1</th>
      <td>단,하나의사랑</td>
      <td>2019년 5월 22일 ~ 2019년  7월 11일</td>
      <td>32부작</td>
      <td>판타지, 로맨스</td>
      <td>KBS 2TV</td>
      <td>조윤정, 정해룡\n  빅토리콘텐츠, 몬스터유니온</td>
      <td>최윤교</td>
      <td>신혜선, 엘 (가수), 이동건, 김보미 (1987년) 외</td>
      <td>2019-05-22 00:00:00</td>
    </tr>
    <tr>
      <th>2</th>
      <td>백일의낭군님</td>
      <td>2018년 9월 10일 ~ 2018년 10월 30일</td>
      <td>16부작</td>
      <td>미스터리 로맨스, 픽션사극</td>
      <td>tvN</td>
      <td>에이스토리\n 이상백</td>
      <td>노지설</td>
      <td>도경수, 남지현 (배우), 조성하 (배우) 외</td>
      <td>2018-09-10 00:00:00</td>
    </tr>
    <tr>
      <th>3</th>
      <td>러브홀릭</td>
      <td>2005년 5월 2일 ~ 2005년 6월 21일</td>
      <td>16부작</td>
      <td>멜로, 드라마</td>
      <td>KBS 2TV</td>
      <td>KBS 2TV 자체제작</td>
      <td>[[이향희 (작가)</td>
      <td>강타, 김규리 (1979년 8월), 이선균, 유인영 외</td>
      <td>2005-05-02 00:00:00</td>
    </tr>
    <tr>
      <th>4</th>
      <td>왜그래풍상씨</td>
      <td>2019년 1월 9일 ~ 2019년 3월 14일</td>
      <td>40부작]] + 스페셜 1부작</td>
      <td>가족, 코미디</td>
      <td>KBS 2TV</td>
      <td>김상헌, 조형진\n  초록뱀미디어, 팬 엔터테인먼트</td>
      <td>문영남</td>
      <td>유준상 (배우), 오지호 (배우), 전혜빈, 이시영 (배우), 이창엽 (배우) 외</td>
      <td>2019-01-09 00:00:00</td>
    </tr>
  </tbody>
</table>

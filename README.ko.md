[English >](https://github.com/jooeungen/coronaboard_kr/blob/master/README.md) 

# 코로나19 대한민국 감염 현황 
질병관리본부에서 제공하는 코로나19(COVID-19)의 국내 감염 현황을 정리했습니다. 

## 코로나보드
- https://coronaboard.kr 에서 시각화 된 데이터를 확인 할 수 있습니다. 

## 데이터 소스 
- 질병관리본부 발표자료 
- http://ncov.mohw.go.kr/

## CSV 데이터 
- 데이터 소스: 질병관리본부 보도자료 (http://ncov.mohw.go.kr/tcmBoardList.do?brdId=3&brdGubun=)
- 공시 예: http://ncov.mohw.go.kr/tcmBoardView.do?brdId=&brdGubun=&dataGubun=&ncvContSeq=354632&contSeq=354632&board_id=&gubun=ALL

#### kr_daily.csv
- 대한민국 코로나19 감염현황: 날짜(date), 누적 확진(confirmed), 누적 사망(death), 누적 격리해제(released), 총 검사자(tested), 결과 음성(negative) 
- 총 검사자 = 검사 중 + 결과 음성 + 결과 확진
- 2020년 1월 21일 데이터 부터 제공 
- 파일 링크: https://github.com/jooeungen/coronaboard_kr/blob/master/kr_daily.csv

#### kr_regional_daily.csv
- 대한민국 지역별 코로나19 감염현황: 날짜, 지역, 누적 확진, 누적 사망, 누적 격리해제
- 검역의 경우 환자의 지역과 상관 없이 공항에서 확진 및 격리된 수 
- 2020년 2월 17일 데이터 부터 제공 
- 파일 링크: https://github.com/jooeungen/coronaboard_kr/blob/master/kr_regional_daily.csv

## 데이터 업데이트 
- 질병관리본부 발표 후 매일 오전 11시에 업데이트 됩니다. 

## 라이센스 
- 학술, 상업, 비상업적 용도로 자유롭게 사용가능합니다. 
- 데이터 사용 시 출처 '코로나보드(coronaboard.kr)' 표시
- 본 사이트에서 제공하는 내용의 인용과 사용에 대한 책임은 전적으로 인용자 및 사용자에게 있음을 알립니다.

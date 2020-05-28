[한국어 >](https://github.com/jooeungen/coronaboard_kr/blob/master/README.ko.md) 

# COVID-19 Situation Report in South Korea
This repository provides CSV format of COVID-19 situation in South Korea reported by [KCDC](http://ncov.mohw.go.kr/).

## Coronaboard website 
- Please visit https://coronaboard.kr for visualized charts and data. 

## Data source 
- KCDC
- http://ncov.mohw.go.kr/

## CSV Data 
- Source: KCDC press release (http://ncov.mohw.go.kr/tcmBoardList.do?brdId=3&brdGubun=)
- example: http://ncov.mohw.go.kr/tcmBoardView.do?brdId=&brdGubun=&dataGubun=&ncvContSeq=354632&contSeq=354632&board_id=&gubun=ALL

#### kr_daily.csv
- COVID-19 situation in South Korea: date, confirmed, death, released, candidate(=test performed), negative
- Tests Performed = tests in progress + negative results + positive results(confirmed cases)
- Data provided since 21st January 2020
- Data link: https://github.com/jooeungen/coronaboard_kr/blob/master/kr_daily.csv

#### kr_regional_daily.csv
- Regional COVID-19 situation in South Korea: date, region, confirmed, death, released 
- Quarantine indicates the number of patients who were screened at the airport. 
- Data provided since 17th February 2020
- Data link: https://github.com/jooeungen/coronaboard_kr/blob/master/kr_regional_daily.csv

## Data update 
- This repository is updated daily at 11am, after KCDC press release. 

## License 
- Available for commercial, non-commercial, research and all other purposes.
- Copyright notice 'Coronaboard(coronaoard.kr)' is needed. 
- We are not responsible for any consequence caused by the use of information provided. 

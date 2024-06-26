# companies-data-scraping

`코스피`, `코스닥`에 상장되어 있는 모든 기업의 ***시가총액***, ***매출액 증가율***, ***PER***, ***ROE***, ***PBR***, ***유보율*** 데이터를 [네이버 증권](https://finance.naver.com/sise/sise_market_sum.naver?&page=1)에서 가져와 `CSV` 파일로 저장시킵니다. 

## How to Use

모든 코스피, 코스닥 상장 기업에 관한 6가지 데이터를 가지고, 자신이 가장 중요하게 생각하는 데이터를 선택하여, 정렬시켜, 그 다음으로 중요하게 생각하는 데이터와의 조합을 판단하여, 분석을 시작할 기업을 선정합니다.

## Example

필자는 ***매출액 증가율***을 가장 중요하게 생각합니다. 왜냐하면, 매출액 증가율이 주주의 자산 증가속도인 ***ROE***의 선행 지표이기 때문입니다. 따라서, 매출액 증가율을 기준으로 기업 리스트를 정렬시켜, 주주의 자산 증가속도와 시장에서 거래되는 기업의 가치 척도인 `ROE`와 `PBR`을 조합하여 분석 기업을 선정합니다.
# Dacon 구직자를 위한 기업 트렌드 시각화
한국고용정보원에서 주최

내가 맡은 부분은 3번째 워크넷 강소기업 API 시각화였다.


- CODE
강소기업 시각화.ipynb는 내가 작성한 것
워크넷 api to csv_강소기업.ipynb : 강소기업 API파일 다운
[구직자를 위한 기업 트렌드 시각화 경진대회] KU MATH 20220126.ipynb : 다 같이 작성한 파일


- twbx
(https://public.tableau.com/views/KUMath_220126_16431921962140/KUMath_220126?:language=ko-KR&:display_count=n&:origin=viz_share_link/sheet0?:showVizHome=no&:embed=true#2) 
다 같이 만든 태블로 결과
기업 시각화 경진대회(KU Math)_220126.twbx 다 같이 만든 스토리
업종 지역별, 업종별 개수, 지역별 강소기업.twbx는 내가 작성한 것

csv
강소기업 API_notnull.csv : 강소기업 데이터 저장된 파일 아래의 피처가 담겨있다.

강소기업 API feature 정보
선정연도 - 오래되었는지 파악하면 좋을 것 같다. (유지 여부?)
강소기업 브랜드명 - 기업내 브랜드(자사 같은 느낌인거 같다...)
기업명 - 시각화에 쓰기 좋은 자료
사업자등록번호 - 다른 데이터와 연결할 때 쓸 수 있을 것 같아서 추가
대표자 - 필요없는 데이터라고 판단하여 생략
업종코드_상, 중 - 다른 데이터와 연결할 때 사용할 수 있다
업종명_상, 중 - 시각화에 쓰기 좋은 자료
사업장 연락처 - 애매하긴하지만, 시각화에 사용해서 연락처를 보여줄 수 있을 것 같아서 추가
지역코드 - 지역을 나타내기 위함
지역명 - 시각화에 사용가능
주소 - 조금 더 자세한 시각화가 가능하면 사용해도 좋을 듯..! 아니면 상세 주소를 표시하는 용도
사업내용 - None 값이 많아서 삭제
주요생산품목 - 기업에서 만드는 품목에 대한 정보 비슷한 기업끼리 분류 가능
기업장점내용 - None 값이 많아서 삭제
회사홈페이지 - 연락처와 마찬가지로 유저들한테 보여주면 좋을만한 내용같아서 추가
상시근로자 수 - 회사의 규모파악에 좋을 듯 하다


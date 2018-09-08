# clien_analysis
clien.net 커뮤니티 분석

# 취지
국정원, 기무사 인터넷 여론조작 등 인터넷 커뮤니티의 건전성이 우려가 되는 요즘
작성자가 이용하는 커뮤니티 클리앙(clien.net)의 모두의 공원 분석을 통해 
특징을 파악하는 목적으로 만들었습니다.

# 주요 쿼리

1. 일정 기간 동안 전체적으로 글을 많이 작성하는 유저

2. 일정 기간 동안 이미지/동영상 위주로 작성하는 유저

3. 본인 글에 댓글을 전혀 달지 않는 작성자

4. 주요 키워드 글을 작성하는 유저

5. 일정 기간 동안 전체적으로 댓글을 많이 작성하는 유저

6 일정 기간 동안 작성자와 댓글 작성자 커플 통계

7. 일정 기간 동안 글 제목에 대한 단어 랭크 (워드클라우드)


# 한계
1) 서버에 부하를 줄이기 위해, 일정시간마다 10페이지를 조회하기 때문에
   나중에 늦게 달리는 댓글은 수집되지 않을 수 있음
2) 제목이나 댓글 내용이 변경되는 것은 인지하지 못할 수 있음
   수집되는 시점의 제목/내용이 수집된다고 보면 되며, 현 시점의 글제목과 댓글 내용과 다를 수 있음
3) 따라서, 원천 데이터가 100% 확실한 것이 아님
4) 커뮤니티의 트랜드 파악으로 참고만 하면 

- [[study]]
-
- [[장부리치]]
	- 2025. 06 ~
	- 서버 2인 / 안드로이드 클라이언트 1인 / iOS 클라이언트 1인 / 기획 및 디자인 2인 (총 6인)
- [[셀스타터]]
	- 2025. 03 ~ 2025. 06
	- 인하대학교 2025-1학기 캡스톤 프로젝트 장려상
	- 서버 1인 / 안드로이드 클라이언트 1인 / AI 1인 (총 3인)
- [[모두의 용기]]
	- 2024. 03 ~ 2024. 06
	- 인하대학교 탄소중립 INNOVATION ACADEMY 우수상
	- 서버 3인 / 안드로이드 클라이언트 2인 (총 5인)
- [[triP]]
	- 2024. 03 ~ 2024. 06
	- 인하대학교 클라우드컴퓨팅 최종 프로젝트
	- iOS 클라이언트 1인 / 서버 2인 / 웹 클라이언트 1인 / 클라우드 아키텍처 1인 (총 6인)
-
- ### index
- query-table:: true
  query-properties:: [:block :page]
  #+BEGIN_QUERY
  {:title [:h3 "TroubleShooting"]
  :query [:find (pull ?b [*])
               :where
                [?p :block/name "troubleshooting"]
                [?b :block/refs ?p]]
  :group-by-page? true}
  #+END_QUERY
- query-sort-by:: block
  query-table:: true
  query-sort-desc:: false
  #+BEGIN_QUERY
  {:title [:h3 "TechIntroduction"]
  :query [:find (pull ?b [*])
               :where
                [?p :block/name "techintroduction"]
                [?b :block/refs ?p]]
  :group-by-page? true}
  #+END_QUERY
- query-table:: true
  #+BEGIN_QUERY
  {:title [:h3 "Springboot"]
  :query [:find (pull ?b [*])
               :where
                [?p :block/name "springboot"]
                [?b :block/refs ?p]]
  :group-by-page? true}
  #+END_QUERY
- query-table:: true
  #+BEGIN_QUERY
  {:title [:h3 "AWS"]
  :query [:find (pull ?b [*])
               :where
                [?p :block/name "aws"]
                [?b :block/refs ?p]]
  :group-by-page? true}
  #+END_QUERY
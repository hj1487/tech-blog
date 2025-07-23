- [[DB ORM 성능 튜닝]]
- [[서버 테스트 코드 작성]]
-
- query-table:: true
  #+BEGIN_QUERY
  {:title [:h3 "Concepts"]
  :query [:find (pull ?b [*])
               :where
                [?p :block/name "concept"]
                [?b :block/refs ?p]]
  :group-by-page? true}
  #+END_QUERY
-
- ### ToDo
- TODO JPA
- TODO cloud native
- TODO design patterns
	- TODO CQRS
-
-
-

              3. Measures to make tests robust and avoid flakiness



   ∙ All tests should be independent of order of execution, data
     multithreading, etc

   ∙ Rotate your test data

   ∙ sources
      - Time dependency
      - Explicit randomness
      - awaiting user interaction in GUI tests
      - OS (path, float point round-off, integer width, default character set)


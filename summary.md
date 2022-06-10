<details>
  <summary>❌ (unexpected) chromium &gt; library/har.spec.ts &gt; examples &gt; my failing test</summary>
  <pre>  [chromium] › library/har.spec.ts:41:3 › examples › my failing test ===============================

    Error: expect(received).toBe(expected) // Object.is equality

    Expected: 2
    Received: 1

      40 |
      41 |   test('my failing test', async ({}) =&gt; {
    &gt; 42 |     expect(1).toBe(2);
         |               ^
      43 |   });
      44 |
      45 |   test('my skip test', async ({}) =&gt; {

        at /Users/rosswollman/code/microsoft/playwright/tests/library/har.spec.ts:42:15

    Retry #1 ---------------------------------------------------------------------------------------

    Error: expect(received).toBe(expected) // Object.is equality

    Expected: 2
    Received: 1

      40 |
      41 |   test('my failing test', async ({}) =&gt; {
    &gt; 42 |     expect(1).toBe(2);
         |               ^
      43 |   });
      44 |
      45 |   test('my skip test', async ({}) =&gt; {

        at /Users/rosswollman/code/microsoft/playwright/tests/library/har.spec.ts:42:15

    Retry #2 ---------------------------------------------------------------------------------------

    Error: expect(received).toBe(expected) // Object.is equality

    Expected: 2
    Received: 1

      40 |
      41 |   test('my failing test', async ({}) =&gt; {
    &gt; 42 |     expect(1).toBe(2);
         |               ^
      43 |   });
      44 |
      45 |   test('my skip test', async ({}) =&gt; {

        at /Users/rosswollman/code/microsoft/playwright/tests/library/har.spec.ts:42:15
</pre>
</details>
<details>
  <summary>❌ (unexpected) chromium &gt; library/har.spec.ts &gt; examples &gt; my timeout test</summary>
  <pre>  [chromium] › library/har.spec.ts:36:3 › examples › my timeout test ===============================

    Timeout of 500ms exceeded.

    Retry #1 ---------------------------------------------------------------------------------------

    Timeout of 500ms exceeded.

    Retry #2 ---------------------------------------------------------------------------------------

    Timeout of 500ms exceeded.
</pre>
</details>
<details>
  <summary>❌ (unexpected) firefox &gt; library/har.spec.ts &gt; examples &gt; my failing test</summary>
  <pre>  [firefox] › library/har.spec.ts:41:3 › examples › my failing test ================================

    Error: expect(received).toBe(expected) // Object.is equality

    Expected: 2
    Received: 1

      40 |
      41 |   test('my failing test', async ({}) =&gt; {
    &gt; 42 |     expect(1).toBe(2);
         |               ^
      43 |   });
      44 |
      45 |   test('my skip test', async ({}) =&gt; {

        at /Users/rosswollman/code/microsoft/playwright/tests/library/har.spec.ts:42:15

    Retry #1 ---------------------------------------------------------------------------------------

    Error: expect(received).toBe(expected) // Object.is equality

    Expected: 2
    Received: 1

      40 |
      41 |   test('my failing test', async ({}) =&gt; {
    &gt; 42 |     expect(1).toBe(2);
         |               ^
      43 |   });
      44 |
      45 |   test('my skip test', async ({}) =&gt; {

        at /Users/rosswollman/code/microsoft/playwright/tests/library/har.spec.ts:42:15

    Retry #2 ---------------------------------------------------------------------------------------

    Error: expect(received).toBe(expected) // Object.is equality

    Expected: 2
    Received: 1

      40 |
      41 |   test('my failing test', async ({}) =&gt; {
    &gt; 42 |     expect(1).toBe(2);
         |               ^
      43 |   });
      44 |
      45 |   test('my skip test', async ({}) =&gt; {

        at /Users/rosswollman/code/microsoft/playwright/tests/library/har.spec.ts:42:15
</pre>
</details>
<details>
  <summary>❌ (unexpected) firefox &gt; library/har.spec.ts &gt; examples &gt; my timeout test</summary>
  <pre>  [firefox] › library/har.spec.ts:36:3 › examples › my timeout test ================================

    Timeout of 500ms exceeded.

    Retry #1 ---------------------------------------------------------------------------------------

    Timeout of 500ms exceeded.

    Retry #2 ---------------------------------------------------------------------------------------

    Timeout of 500ms exceeded.
</pre>
</details>
<details>
  <summary>❌ (unexpected) webkit &gt; library/har.spec.ts &gt; examples &gt; my failing test</summary>
  <pre>  [webkit] › library/har.spec.ts:41:3 › examples › my failing test =================================

    Error: expect(received).toBe(expected) // Object.is equality

    Expected: 2
    Received: 1

      40 |
      41 |   test('my failing test', async ({}) =&gt; {
    &gt; 42 |     expect(1).toBe(2);
         |               ^
      43 |   });
      44 |
      45 |   test('my skip test', async ({}) =&gt; {

        at /Users/rosswollman/code/microsoft/playwright/tests/library/har.spec.ts:42:15

    Retry #1 ---------------------------------------------------------------------------------------

    Error: expect(received).toBe(expected) // Object.is equality

    Expected: 2
    Received: 1

      40 |
      41 |   test('my failing test', async ({}) =&gt; {
    &gt; 42 |     expect(1).toBe(2);
         |               ^
      43 |   });
      44 |
      45 |   test('my skip test', async ({}) =&gt; {

        at /Users/rosswollman/code/microsoft/playwright/tests/library/har.spec.ts:42:15

    Retry #2 ---------------------------------------------------------------------------------------

    Error: expect(received).toBe(expected) // Object.is equality

    Expected: 2
    Received: 1

      40 |
      41 |   test('my failing test', async ({}) =&gt; {
    &gt; 42 |     expect(1).toBe(2);
         |               ^
      43 |   });
      44 |
      45 |   test('my skip test', async ({}) =&gt; {

        at /Users/rosswollman/code/microsoft/playwright/tests/library/har.spec.ts:42:15
</pre>
</details>
<details>
  <summary>❌ (unexpected) webkit &gt; library/har.spec.ts &gt; examples &gt; my timeout test</summary>
  <pre>  [webkit] › library/har.spec.ts:36:3 › examples › my timeout test =================================

    Timeout of 500ms exceeded.

    Retry #1 ---------------------------------------------------------------------------------------

    Timeout of 500ms exceeded.

    Retry #2 ---------------------------------------------------------------------------------------

    Timeout of 500ms exceeded.
</pre>
</details>
<details>
  <summary>⁉️ (flaky) chromium &gt; library/har.spec.ts &gt; examples &gt; my flaky test</summary>
  <pre>  [chromium] › library/har.spec.ts:28:3 › examples › my flaky test =================================

    Error: expect(received).toBe(expected) // Object.is equality

    Expected: 1
    Received: 0

      27 | test.describe.only('examples', () =&gt; {
      28 |   test('my flaky test', async ({}, testInfo) =&gt; {
    &gt; 29 |     expect(testInfo.retry).toBe(1);
         |                            ^
      30 |   });
      31 |
      32 |   test('my passing test', async ({}) =&gt; {

        at /Users/rosswollman/code/microsoft/playwright/tests/library/har.spec.ts:29:28
</pre>
</details>
<details>
  <summary>⁉️ (flaky) firefox &gt; library/har.spec.ts &gt; examples &gt; my flaky test</summary>
  <pre>  [firefox] › library/har.spec.ts:28:3 › examples › my flaky test ==================================

    Error: expect(received).toBe(expected) // Object.is equality

    Expected: 1
    Received: 0

      27 | test.describe.only('examples', () =&gt; {
      28 |   test('my flaky test', async ({}, testInfo) =&gt; {
    &gt; 29 |     expect(testInfo.retry).toBe(1);
         |                            ^
      30 |   });
      31 |
      32 |   test('my passing test', async ({}) =&gt; {

        at /Users/rosswollman/code/microsoft/playwright/tests/library/har.spec.ts:29:28
</pre>
</details>
<details>
  <summary>⁉️ (flaky) webkit &gt; library/har.spec.ts &gt; examples &gt; my flaky test</summary>
  <pre>  [webkit] › library/har.spec.ts:28:3 › examples › my flaky test ===================================

    Error: expect(received).toBe(expected) // Object.is equality

    Expected: 1
    Received: 0

      27 | test.describe.only('examples', () =&gt; {
      28 |   test('my flaky test', async ({}, testInfo) =&gt; {
    &gt; 29 |     expect(testInfo.retry).toBe(1);
         |                            ^
      30 |   });
      31 |
      32 |   test('my passing test', async ({}) =&gt; {

        at /Users/rosswollman/code/microsoft/playwright/tests/library/har.spec.ts:29:28
</pre>
</details>
# Lighthouse

## Lighthouse 초기 지표
  - 초기 성능 : 🟠 86점 
  - 초기 접근성 : 🟠 82점
  - 초기 권장사항 : 🟠 78점
  - 초기 SEO : 🟠 82점

## Lighthouse 1차 개선
   - 성능 : 🟠 88점
   - 접근성 : 🟢 91점
   - 권장사항 : 🟠 79점
   - SEO : 🟢 100점
<br/>

✘  color-contrast failure for minScore assertion
       Background and foreground colors do not have a sufficient contrast ratio.
       <br/>배경색과 전경색의 대비율이 충분하지 않습니다.<br/>
       https://dequeuniversity.com/rules/axe/4.9/color-contrast

        expected: >=0.9
           found: 0
      all values: 0, 0, 0


  ✘  errors-in-console failure for minScore assertion
       Browser errors were logged to the console
       <br/>브라우저 콘솔에 오류가 기록되었습니다<br/>
       https://developer.chrome.com/docs/lighthouse/best-practices/errors-in-console/

        expected: >=0.9
           found: 0
      all values: 0, 0, 0


  ✘  heading-order failure for minScore assertion
       Heading elements are not in a sequentially-descending order
       <br/>제목 요소들이 순차적으로 내림차순으로 정렬되어 있지 않음<br/>
       https://dequeuniversity.com/rules/axe/4.9/heading-order

        expected: >=0.9
           found: 0
      all values: 0, 0, 0


  ✘  lcp-lazy-loaded failure for minScore assertion
       Largest Contentful Paint image was not lazily loaded
       <br/>LCP(Largest Contentful Paint) 이미지가 지연 로딩되지 않았습니다<br/>
       https://web.dev/articles/lcp-lazy-loading
           found: 24
      all values: 24, 24, 24


  ✘  uses-text-compression failure for maxLength assertion
       Enable text compression
       <br/>텍스트 압축 활성화<br/>
       https://developer.chrome.com/docs/lighthouse/performance/uses-text-compression/

        expected: <=0
           found: 3
      all values: 3, 3, 3


  ⚠️  first-contentful-paint warning for minScore assertion
       First Contentful Paint <br/>첫 번째 콘텐츠가 그려지는 시간<br/>
       https://developer.chrome.com/docs/lighthouse/performance/first-contentful-paint/

        expected: >=0.9
           found: 0.83
      all values: 0.72, 0.83, 0.83


  ⚠️  is-on-https warning for minScore assertion
       <br/>HTTPS를 사용하지 않음<br/>
       https://developers.google.com/web/fundamentals/security/prevent-mixed-content/what-is-mixed-content

        expected: >=0.9
           found: 0
      all values: 0, 0, 0


  ⚠️  largest-contentful-paint warning for minScore assertion
       <br/>가장 큰 콘텐츠가 그려지는 시간<br/>
       https://developer.chrome.com/docs/lighthouse/performance/lighthouse-largest-contentful-paint/

        expected: >=0.9
           found: 0.61
      all values: 0.17, 0.61, 0.61


  ⚠️  modern-image-formats warning for maxLength assertion
       <br/>차세대 이미지 포맷으로 제공<br/>
       https://developer.chrome.com/docs/lighthouse/performance/uses-webp-images/

        expected: <=0
           found: 12
      all values: 12, 12, 12


  ⚠️  uses-long-cache-ttl warning for maxLength assertion
       <br/>정적 자산에 효율적인 캐시 정책 적용<br/>
       https://developer.chrome.com/docs/lighthouse/performance/uses-long-cache-ttl/

        expected: <=0
           found: 30
      all values: 30, 30, 30


## Lighthouse 2차 개선
<div align="center">

<img src="./assets/noir.svg" alt="onevilx — security researcher" width="100%">

<a href="https://www.onevilx.tech"><img alt="site" src="https://img.shields.io/badge/onevilx.tech-0b0b0b?style=for-the-badge&logo=firefoxbrowser&logoColor=a8a8a8&labelColor=0b0b0b"></a>
<a href="https://www.onevilx.tech/archive/"><img alt="write-ups" src="https://img.shields.io/badge/write--ups-0b0b0b?style=for-the-badge&logo=hackthebox&logoColor=a8a8a8&labelColor=0b0b0b"></a>
<a href="https://app.intigriti.com/profile/onevilx"><img alt="intigriti" src="https://img.shields.io/badge/intigriti-0b0b0b?style=for-the-badge&logo=intigriti&logoColor=a8a8a8&labelColor=0b0b0b"></a>
<a href="https://github.com/onevilx?tab=repositories"><img alt="repos" src="https://img.shields.io/badge/repos-0b0b0b?style=for-the-badge&logo=github&logoColor=a8a8a8&labelColor=0b0b0b"></a>

</div>

### Advisories

| | | |
|---|---|---|
| [`GHSA-g2v6-rqmx-r4w6`](https://github.com/vuejs/core/security/advisories/GHSA-g2v6-rqmx-r4w6) | `@vue/server-renderer` | SSR XSS via a carriage return in an attribute name &nbsp;·&nbsp; **High 7.2** |
| [`GHSA-87xc-4hwr-pxf6`](https://github.com/danielcompton/ip-range-check/security/advisories/GHSA-87xc-4hwr-pxf6) | `ip-range-check` | SSRF filter bypass with non-canonical IPv4 &nbsp;·&nbsp; **Moderate** |
| [`GHSA-xc49-mgwh-9pjv`](https://github.com/atinux/nuxt-auth-utils/security/advisories/GHSA-xc49-mgwh-9pjv) | `nuxt-auth-utils` | OAuth `state` unvalidated in 35 of 48 providers &nbsp;·&nbsp; **Moderate** |

### Write-ups

[Vue SSR XSS](https://www.onevilx.tech/posts/vue-ssr-xss-missing-cr/) &nbsp;·&nbsp;
[IPv4 SSRF bypass](https://www.onevilx.tech/posts/ip-range-check-ssrf-bypass/) &nbsp;·&nbsp;
[OAuth state](https://www.onevilx.tech/posts/nuxt-auth-utils-oauth-csrf/) &nbsp;·&nbsp;
[CORS on localhost](https://www.onevilx.tech/posts/cors-credentialed-localhost-reflection/) &nbsp;·&nbsp;
[Intigriti BRP](https://www.onevilx.tech/posts/intigriti-brp-dom-xss/) &nbsp;·&nbsp;
[coupon stacking](https://www.onevilx.tech/posts/intigriti-1026-coupon-stacking/) &nbsp;·&nbsp;
[base64 SQLi](https://www.onevilx.tech/posts/intigriti-0926-sqli-base64/)

### Hunting

Broken access control &nbsp;·&nbsp; OAuth and session binding &nbsp;·&nbsp; parser differentials &nbsp;·&nbsp; DOM XSS &nbsp;·&nbsp; business logic

Burp &nbsp;·&nbsp; Python &nbsp;·&nbsp; Playwright &nbsp;·&nbsp; `ffuf` &nbsp;·&nbsp; `nuclei` &nbsp;·&nbsp; Semgrep

Software engineering at **1337 / 42 Network**.

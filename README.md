# π° Crypto Tracker

## π Skills

- React(CRA with TypeScript), react-router-dom, react-helmet-async, styled-components, react-query, [coin paprika API](https://api.coinpaprika.com/v1/coins), [Crypto Icon API](https://cryptocurrencyliveprices.com/), [JSON QuickType](https://app.quicktype.io/?l=ts), [APEX CHARTS](https://apexcharts.com)

## π Deploy URL

- [https://dingunote.github.io/top100-crypto-tracker/](https://dingunote.github.io/top100-crypto-tracker/)

## π Page Directory

- `/`: λ©μΈ νμ΄μ§ λͺ¨λ  μ½μΈ λͺ©λ‘
- `/:id`: ν΄λΉ idλ₯Ό κ°μ§κ³  μλ μ½μΈμ μμΈ μ λ³΄
- `/:id/chart`: ν΄λΉ μ½μΈμ μ°¨νΈ μ λ³΄
- `/:id/price`: ν΄λΉ μ½μΈμ κ°κ²© μ λ³΄

## π File Path

```bash
βββ public                     Static Files
β
βββ src
    βββ routes
    β   βββ Coins.tsx          Main Page
    β   βββ Coin.tsx           Detail Page
    β   βββ Chart.tsx          Detail/Chart Page
    β   βββ Price.tsx          Detail/Price Page
    βββ api.tsx                API Source
    βββ App.tsx
    βββ index.tsx
    βββ GlobalStyle.tsx        Global Style Component
    βββ Router.tsx             Router Component
    βββ theme.tsx             Theme Component
```

## π Issue

- coin-paprika APIκ° μ λ£ν λλ λ°λμ μμλ‘ λ€λ₯Έ APIλ₯Ό μ¬μ©νμ§λ§ μ€κ° μ€κ° μ½μΈμ μ±ν¬κ° λ§μ§ μμ νΉμ  μ½μΈμ μ°¨νΈμ κ°κ²© μ λ³΄λ₯Ό νμΈν  λ λ°μ΄ν°κ° μμ΄μ μλ¬ λ°μ

## π Features

- Dark Mode / Light Mode κΈ°λ₯ μΆκ°
  1. stateλ₯Ό μ¬μ©νκΈ° μν΄ κΈ°μ‘΄μ `index.tsx`μμ Providing νλ ThemeProviderμ themeλ₯Ό App.tsxλ‘ μ΄λ
  2. `theme.ts`μ Dark Theme, Light Theme μΆκ°
  3. ApexCharts λΌμ΄λΈλ¬λ¦¬μλ Dark Mode, Light Mode μΌ λ Chart μμ²΄μ Dark, Light Mode μ΅μμ μ¬μ©νκ³  μΆμΌλ, Prop Drilling λ°μ
  4. `Recoil`μ μ¬μ©ν΄μ isDark Atomμ μμ±ν ν App μ»΄ν¬λνΈμ Chart μ»΄ν¬λνΈμμ μν κ°μ κ°μ Έμμ μ¬μ©

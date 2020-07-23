````sh
npx https://github.com/prototypicalpro/repolinter.git lint -r repolinter-normal.json .
npx https://github.com/prototypicalpro/repolinter.git lint -d -r repolinter-fix.json .
npx https://github.com/prototypicalpro/repolinter.git lint -r repolinter-fix.json .
npx https://github.com/prototypicalpro/repolinter.git lint .
npx https://github.com/prototypicalpro/repolinter.git lint -d -u https://raw.githubusercontent.com/aperture-science-incorporated/.github/master/repolinter.json .
```
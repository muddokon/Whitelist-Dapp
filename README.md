# Whitelist Dapp

I made this while studying Solidity development and deployment.

It uses:
- Frontend: React.
- Backend: NextJS.
- Smart Contracts: Solidity.
- Deployment: Hardhat.

If you find it useful, please refer to learnweb3.io

UPDATE:

Original code provided had an issue with img tags due to NextJS requirement of wrapping them up in picture or Image tags before build:
https://nextjs.org/docs/messages/no-img-element

Worked it around like this:

```html
<picture>
  <source srcSet="/kid.jpg" type="image/jpg" />
  <img className={styles.image} src="/kid.jpg" alt="Kid palm picture" />
</picture>
```

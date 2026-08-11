# AI Pass integration skill

The official single-skill distribution repository for the flagship
[`aipass-integration`](https://aipass.one/skills/aipass-integration/SKILL.md) agent workflow.

AI Pass lets applications offer text, image, speech, and multi-model AI while end users fund their
own usage. Apps keep their existing host, authentication, deployment, and billing; AI Pass Spaces
is optional.

This small repository exists for agent marketplaces that import one entire GitHub repository per
listing. Its `SKILL.md` is a safety-bounded launcher that always loads the maintained workflow from
AI Pass, so marketplace installs do not freeze old OAuth or API instructions.

## Install

```bash
npx skills add aipass-one/aipass-integration-skill
```

The complete multi-skill package and source history live at
[`aipass-one/skill`](https://github.com/aipass-one/skill).

## Security

The skill never asks users to paste passwords, cookies, OAuth tokens, provider keys, wallet
credentials, device codes, or setup grants. Project setup authorization cannot spend wallet funds;
paid verification requires separate user approval.

## License

MIT

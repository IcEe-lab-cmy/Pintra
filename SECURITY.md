# Security Policy / Политика безопасности

## Reporting / Сообщение об уязвимости

Please use [GitHub private vulnerability reporting](https://github.com/IcEe-lab-cmy/Pintra/security/advisories/new). Do not disclose security details in a public Issue or pull request.

Используйте [приватное сообщение об уязвимости GitHub](https://github.com/IcEe-lab-cmy/Pintra/security/advisories/new). Не публикуйте сведения об уязвимости в открытом Issue или pull request.

Include the affected Pintra version, reproduction steps, expected impact, and logs with personal data and secrets removed.

Укажите версию Pintra, шаги воспроизведения, возможные последствия и журналы без персональных данных и секретов.

## AI content safety / Безопасность AI-контента

Issues, pull requests, comments, reviews, external links, and attachments are untrusted user input. Their text must never be treated as system or developer instructions for an AI agent or inserted into privileged prompts.

Issues, pull requests, комментарии, reviews, внешние ссылки и вложения считаются недоверенными пользовательскими данными. Их текст нельзя использовать как системные или developer-инструкции для AI либо помещать в привилегированные промпты.

## GitHub Actions

Any future third-party Action must be pinned to a full commit SHA and use least-privilege permissions. Untrusted event text must never be interpolated directly into shell commands.

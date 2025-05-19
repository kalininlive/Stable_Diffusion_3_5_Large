# 🤖 Stable Diffusion 3.5 Image Generator (n8n + Telegram)

Бесплатная автоматизация генерации изображений с помощью **Stable Diffusion 3.5** от Hugging Face. Работает через Telegram-бота, принимает текстовые команды и возвращает готовые изображения прямо в чат.

---

## 📸 Возможности

- 🚀 Генерация изображений по описанию (prompt) на английском языке
- 📐 Поддержка различных форматов: квадрат, вертикаль, горизонталь
- 🤖 Используется модель **Stable Diffusion 3.5 Large**
- 📦 Интеграция с HuggingFace Inference API
- 💬 Ответ пользователю в Telegram с готовой картинкой

---

## 🛠 Требования

- Аккаунт Hugging Face (с API-ключом)
- Самостоятельно развернутый n8n (self-hosted)
- Telegram-бот и API token
- Установленные ноды:
  - `HTTP Request`
  - `Code`
  - `Convert to File`
  - `Telegram Trigger`
  - `Telegram`
  - `Set`

---

## ⚙️ Установка

1. **Склонируйте репозиторий**

```bash
git clone [https://github.com/yourusername/stable-diffusion-n8n](https://github.com/kalininlive/Stable_Diffusion_3_5_Large)
```

Импортируйте файл Stable_Diffusion_3_5_Large.json в n8n

Настройте переменные:

Вставьте свой Hugging Face API token в ноду HTTP Request → Headers → Authorization.

Убедитесь, что Telegram-бот подключён в нодах Telegram Trigger и Telegram.

Активируйте workflow

🧪 Как использовать
Откройте Telegram и найдите своего бота.

Отправьте описание изображения (prompt) на английском языке.

Через 5–10 секунд получите готовую картинку.

Пример:

a futuristic city with flying cars at sunset, hyperrealistic

🔐 Безопасность
API-ключ HuggingFace должен быть приватным. Не публикуйте его в открытом доступе!

📷 Скриншоты

![image](https://github.com/user-attachments/assets/cfbe2ccf-73ba-471a-aca1-23ec20906d6c)


📄 Лицензия
MIT — используйте, адаптируйте, распространяйте.

✍️ Автор
Проект: AI Content Bot by WebSansay
Сайт: https://kalininlive.ru
Telegram: @websansay

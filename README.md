**Генерация стикеров с помощью ввода картинки-референса и текстового описания:**
* Стикерпак для обучения LoRA: Pusheen The Cat, разметка при помощи LlavaNext (https://huggingface.co/datasets/ktrndy/pusheen)
* DreamBooth fine-tuning c базовой моделью stable-diffusion-v1-5/stable-diffusion-v1-5 и LoRA на размеченном датасете
* Полученная LoRA загружена на Hugging Face: https://huggingface.co/spaces/ktrndy/diffusion-image-gen
* Добавлены возможности:
  - подключения ControlNet и IpAdapter
  - использования Tiny VAE и DDIM солвера
  - использования дистиллированных моделей (nota-ai/bk-sdm-v2-base и -small) вместо стандартной SD 1.5
* Лучшие результаты тестовых генераций собраны в стикерпак из 10 разных картинок: https://t.me/addstickers/pusheen_by_diffusion_by_fStikBot

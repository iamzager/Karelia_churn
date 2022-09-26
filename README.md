# Karelia_churn
Прогнозирование оттока пользователей провайдера телекоммуникационных услуг
Скринкаст с объяснением работы: https://drive.google.com/file/d/1Jvc_nNz0UzBXtXC5tI-IFSnqjPdmRCJE/view?usp=sharing
- Karelia_main: основной файл, содержит создание признаков, обучение модели, валидацию и прогноз
- Karelia_tuning: файл для подбора гиперпараметров. Использует признаки, рассчитанные в Karelia_main, и сохраняет итоговые параметры в виде json файлов
- best_params, meta_best_params: подобранные гиперпараметры для основного и мета-алгоритма

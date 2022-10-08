<h1>
  Цифровой прорыв 2022.<br>
  Региональный чемпионат республики Карелия.
</h1>

## Задача
Прогнозирование оттока пользователей провайдера телекоммуникационных услуг.<br>
Бинарная классификация лояльных и нелояльных клиентов

### Исходные данные
dns_log.csv - логи обращений клиентов к сервисам конкурентов<br>
support_log.csv - логи обращений клиентов в службу поддержки<br>
type_contract.csv - схема оплаты клиента: посуточная или помесячная

### Метрика
Простая средняя полнота по обоим классам (macro average recall) 

## Решение
- Karelia_EDA - разведочный анализ и создание признаков
- Karelia_main - Основной файл. Расчет признаков, обучение и валидация модели, прогноз
- Karelia_tuning - Подбор гиперпараметров для основного (best_params.json) и мета-алгоритма (meta-best_params.json)

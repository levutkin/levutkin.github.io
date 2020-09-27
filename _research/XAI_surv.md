---
title: "Интерпретация моделей выживаемости"
collection: research
type: ""
permalink: /research/XAI_surv
venue: "СПбПУ"
date: 2020-06-28
location: ""
---

Завершен первый цикл работ по разработке новых методов интерпретации моделей машинного обучения для анализа выживаемости (survival analysis), который случайно начался в январе этого года (хотя ничего случайного не бывает). 

**Авторы** - аспирант Максим Ковалев и магистрант Эрнест Касимов (уже магистр) и их научный руководитель, являющиеся сотрудниками лаборатории нейросетевых технологий и искусственного интеллекта Политеха.

Рассматриваемая задача относится к направлению работ в машинном обучении, которые можно объединить названием «объяснительный интеллект», «методы интерпретации» или «eXplainable Artificial Intelligence (XAI)». Основной задачей, решаемой методами объяснения и интерпретации, является определение наиболее значимых признаков данных, которые привели (или не привели) к определенному решению, "принимаемому" моделью машинного обучения (классификатором или регрессором), рассматриваемой как «черный ящик». В работах предлагаются локальные модели интерпретации и объяснения, когда анализируется решение, связанное с отдельным примером, например, диагноз отдельного пациента. Особенность цикла работ заключается в том, что решение модели машинного обучения - это функция выживаемости или кумулятивная функция риска. Фактически мы пытаемся определить те признаки, которые привели к определенной функции выживаемости (factual explanation), или определить, значения каких признаков нужно изменить и как, чтобы получить требуемую функцию выживаемости (counterfactual explanation). Предлагаемые методы могут применяться в самых различных областях, но наиболее интересные применения - это области медицины, где методы машинного обучения приобретают с каждым днем все большее значение в задачах диагностики и выбора оптимального вида лечения.

**Список препринтов и публикаций:**

1. Kovalev M.S., Utkin L.V., Kasimov E.M. SurvLIME: A method for explaining machine learning survival models // arXiv:2003.08371. Mar. 2020.  <https://arxiv.org/abs/2003.08371/>
2. (Расширенная версия, опубликованная в журнале) Kovalev M.S., Utkin L.V., Kasimov E.M. SurvLIME: A method for explaining machine learning survival models // Knowledge-Based Systems, vol. 203, p. 106164, 2020. DOI: 10.1016/j.knosys.2020.106164  <https://www.sciencedirect.com/science/article/pii/S0950705120304044/>
3. Utkin L.V., Kovalev M.S., Kasimov E.M. SurvLIME-Inf: A simplified modification of SurvLIME for explanation of machine learning survival models // arXiv:2005.02387, May 2020. <https://arxiv.org/abs/2005.02387/>
4. Kovalev M.S., Utkin L.V. A robust algorithm for explaining unreliable machine learning survival models using the Kolmogorov-Smirnov bounds // arXiv:2005.02249, May 2020. <https://arxiv.org/abs/2005.02249/>
5. (Расширенная версия, опубликованная в журнале) Kovalev M.S. Utkin L.V. A robust algorithm for explaining unreliable machine learning survival models using the Kolmogorov-Smirnov bounds // Neural Networks, vol. 132, pp. 1-18, 2020. DOI: 10.1016/j.neunet.2020.08.007 https://www.sciencedirect.com/science/article/pii/S0893608020302963
6. Kovalev M.S., Utkin L.V. Counterfactual explanation of machine learning survival models // arXiv: 2006.16793, June 2020. <https://arxiv.org/abs/2006.16793/>

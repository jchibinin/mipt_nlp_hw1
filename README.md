# Dr.House Retreival bot 

Бот берет фразы с kaggle датасета, прообразует их в формат вопрос-ответ, ответ обязательно Хауса, затем векторизует и ищет похожий вопрос через cosine_similarity, упорядочивает похожие вопросы и берет первый по релевантности, возвращает ответ на вопрос (общение с ботом на английском языке). Интерфейс реализован через Gradio

Пробовал реализовать через TfIdf но результат был неудвлетоврительный. Через векторные СУБД тоже показалось слишком для такой задачи, остановился на промежуточном варианте

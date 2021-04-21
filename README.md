# Insta

Есть модели поста, лайка и комментария.

InstaDao отвечает за readOnly действия и выдаёт посты через PostDisplay

AddComment/Like/Post наследуются от команды и содержат данные о сущности

CommandHandler обрабатывает пигущие команды

# Используем официальный образ Freqtrade
FROM freqtradeorg/freqtrade:stable

# Устанавливаем рабочую директорию
WORKDIR /freqtrade

# Копируем пользовательские данные (настройки, стратегии)
COPY user_data /freqtrade/user_data

# Указываем правильную команду запуска
CMD ["trade", "--config", "/freqtrade/user_data/config.json", "--strategy", "Strategy005"]

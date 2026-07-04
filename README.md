# bot.py
    import os    from telegram.ext import Application    TELEGRAM_TOKEN = os.getenv("TELEGRAM_TOKEN")    PROMPT_RAHASIA = os.getenv("PROMPT_RAHASIA")    def main():        print("Bot GEBOM Jalan...")        app = Application.builder().token(TELEGRAM_TOKEN).build()        app.run_polling()    if __name__ == "__main__":        main()

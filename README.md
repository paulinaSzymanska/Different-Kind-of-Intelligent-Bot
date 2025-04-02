## ENG

### Requirements:
A text-based application simulating a conversation with a human.

The application should consist of a conversation display area, a text input field for typing messages, and a send button.

Initially, the conversation area should display a welcome message from the bot, e.g., "Hi, how are your JS classes going?"

The user can type any message in the text input field and confirm it with the send button, which will add their message to the conversation window and clear the input field.

The user should also be able to send a message using the Enter key.

The bot should respond to each user message with its own message.

The content of the bot's responses is not important, but it must be deterministic (always responding the same way to the same user input).
Prepare at least three different responses.

### Additional Features
The bot's message should not appear instantly. Simulate a short delay before the bot responds.

Implement a profanity detection mechanism (e.g., "dang it"). If the user tries to send a message with forbidden words,
they should receive an alert, and instead of their message appearing in the conversation, the bot should display a red message:
"Please, do not use such words."

Provide commands for the bot:
* /version → Example response: Software version: v1.2.3
* /weather krakow → Example response (fictional): In Krakow, it's 22 degrees.

## PL

### Wymagania: 

Aplikacja udająca rozmowę z człowiekiem w formie tekstowej.

aplikacja powinna składać się z pola na treść rozmowy, pola tekstowego umożliwiającego wpisywanie tekstu oraz przycisku wysyłającego wiadomość
Na początku w polu z treścią rozmowy powinna pojawić się wiadomość powitalna od bota, np. Cześć, jak tam zajęcia z JS?
W polu tekstowym pod treścią użytkownik może wpisać dowolną wiadomość i potwierdzić ją przyciskiem, co spowoduje pojawienie
się jego wiadomości w oknie rozmowy i wyczyszczenie pola tekstowego
Wiadomość użytkownika powinno dać się wysłać za pomocą klawisza Enter
Na każdą wiadomość bot powinien odpowiedzieć kolejną wiadomością od siebie
Nie jest istotne, co bot będzie odpowiadać, ale ważne by był on deterministyczny (odpowiadał zawsze tak samo na tę 
samą wiadomość od użytkownika). Przygotuj przynajmniej trzy różne odpowiedzi.

### Dodatkowe funkcje

Wiadomość bota nie powinna pojawić się natychmiast. Zasymuluj, że bot chwilę tworzy swoją wiadomość.
Dostarcz mechanizm wykrywania wulgaryzmów (np. motyla noga). Jeśli użytkownik spróbuje wysłać wiadomość z zabronioną treścią, powinien otrzymać ostrzeżenie (alert), a w oknie rozmowy, zamiast wiadomości użytkownika powinien pojawić się czerwony wpis od bota proszę, nie używaj takich słów
Dostarcz komendy dla bota:
/version, przykładowa odpowiedź: Wersja oprogramowania: v1.2.3
/pogoda kraków, przykładowa odpowiedź (zmyślona): W kraków jest 22 stopnie

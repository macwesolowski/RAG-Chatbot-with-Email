# RAG-Chatbot-with-Email

🤖 Przedstawiam Agenta AI wspierającego analizy finansowe i decyzje biznesowo-inwestycyjne on-line.
To zaawansowane połączenie RAG (Retrieval-Augmented Generation) z chatbotem oraz możliwością automatycznego wysyłania maili z poziomu rozmowy 💬📧

🎯 Celem agenta jest usprawnienie analizy danych finansowych i umożliwienie szybkiego generowania raportów oraz insightów – np. pod kątem oceny opłacalności inwestowania w produkty Google lub ogólnej kondycji finansowej firmy Google.

🛠️ Stack (użyte technologie):
 n8n, Google Drive, Pinecone, OpenAI, Gmail

📂 Jak to działa? Na Google Drive umieściłem pliki PDF z wynikami finansowymi firmy Alphabet (Google) za Q4 2024 i Q1 2025.

🧠 Agent AI wykrywa nowe pliki i zapisuje ich zawartość w wektorowej bazie danych Pinecone – co umożliwia semantyczne wyszukiwanie i analizę treści.

💬 Za pomocą chatbota mogę zadawać pytania dotyczące dokumentów i otrzymywać syntetyczne odpowiedzi oraz analizy generowane przez ChatGPT.

📧 Na życzenie/żądanie, chatbot wysyła maila z podsumowaniem, porównaniem danych i rekomendacjami – wszystko w ramach jednej rozmowy.

⚙️ Chatbot działa obecnie lokalnie (localhost), ale daje ogromne możliwości w zakresie automatyzacji analiz i wsparcia decyzyjnego w biznesie, pod wrzuceniu go na serwer.

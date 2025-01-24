## Groupe
    * Paul GIRAUD

## Comment récupérer mon code et l'exécuter

###     1. Lancez un terminal et exécutez la commande ci dessous :
    git clone https://github.com/PaulGrd/streamlitbot.git

###     2. Installez les librairies nécessaires à l'exécution du code Python :
    pip install -r requirements.txt

###     3. Créez un dossier .streamlit et un fichier secrets.toml à l'intérieur

###     4. Copiez ce code en remplaçant YOUR_API_KEY par votre clé API OpenAI :
    # .streamlit/secrets.toml
    OPENAI_API_KEY = "YOUR_API_KEY"

###     5. Pour tester le chatbot, exécutez cette commande :
    streamlit run chatbotgpt.py
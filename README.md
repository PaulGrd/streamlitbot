## Groupe
    * Paul GIRAUD

## Comment récupérer mon code et l'exécuter

###     1. Lancez un terminal et exécutez la commande ci dessous :
    git clone https://github.com/PaulGrd/streamlitbot.git

###     2. Ensuite exécutez la commande suivante pour créer un environnement virtuel:
    python -m venv stenv

###     3. Pour utiliser un environnement python que nous venons de créer et qui s'appelle stenv, entrez ce qui suit dans la ligne de commande :
    source stenv/bin/activate 

###     4. Installez les librairies nécessaires à l'exécution du code Python :
    pip install -r requirements.txt

###     5. Créez un dossier .streamlit et un fichier secrets.toml à l'intérieur de ce dossier

###     6. Copiez ce code dans le fichier secrets.toml en remplaçant YOUR_API_KEY par votre clé API OpenAI :
    # .streamlit/secrets.toml
    OPENAI_API_KEY = "YOUR_API_KEY"

###     7. Pour tester le chatbot, exécutez cette commande :
    streamlit run chatbotgpt.py
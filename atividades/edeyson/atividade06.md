**Atividade sobre Tradução**  
  

**Questões**  

**Parte 1**  

-   Há partes do projeto (interface de usuário, documentação, website) preparadas para tradução ("internationalization" - I18N)?
	- Não. A tradução é via arquivos json, mapeando de inglês para outro idioma. Por exemplo, o arquivo https://github.com/TheAlgorithms/website/blob/main/public/locales/es/categories.json:

			"conversions": "Conversiones",
			"computervision": "Visión de ordenador",
			"compression": "Compresión",
			"complementaryfilter": "Filtro complementario",
			"clusteringalgorithms": "Agrupación de algoritmos",
			"clientserver": "Cliente Servidor",
			"classificationalgorithms": "Algoritmos de clasificación",
			"ciphers": "Cifras",
			"cellularautomata": "Celular Automata",

-   Quais as ferramentas usadas para apoiar o processo de tradução ("localization" - L10N)?
	- A tradução no projeto é feita via Weblate: https://hosted.weblate.org/engage/TheAlgorithms/?utm_source=widget
	
-   Qual o formato utilizado?
	- Utiliza-se um arquivo texto (.json) com as traduções.
-   Há uma equipe fazendo tradução para Português do Brasil (pt-br)?
	- Não, ainda não há projeto para o Português.
	- Os idiomas suportados são: Inglês, Alemão, Chinês, Croata, Espanhol, Esperanto, Hindi, Italiano, Russo e Ucraniano.


**Parte 2**

-   Faça uma contribuição de tradução ao projeto e envie um patch.
	- Fiz traduções do inglês para o espanhol.
 
-   Qual foi o feedback que você recebeu dos desenvolvedores do projeto?
	- O Feedback ocorre no Weblate como em: [Textos que necessitam ação — 103 palavras](https://hosted.weblate.org/translate/TheAlgorithms/categories/es/?q=state:%3Ctranslated)
	- Os revisores podem confirmar as alterações. 

	- As contribuições feitas podem ser recuperadas no Weblate via histórico pessoal do colaborador. Por exemplo, um de meus históricos:

			[{"source": "Audio", "target": "Audio", "source_language": "en", "target_language": "es", "origin": "TheAlgorithms/categories", "category": 20036568}, {"source": "Binary", "target": "Binario", "source_language": "en", "target_language": "es", "origin": "TheAlgorithms/categories", "category": 20036568}, {"source": "Binary Tree", "target": "\u00c1rbol Binario", "source_language": "en", "target_language": "es", "origin": "TheAlgorithms/categories", "category": 20036568}, {"source": "Binary Search Tree", "target": "\u00c1rbol Binario de B\u00fasqueda", "source_language": "en", "target_language": "es", "origin": "TheAlgorithms/categories", "category": 20036568}]

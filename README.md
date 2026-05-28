# NLP and Speech Processing Projects
In this repository you can find two types of projects: text preprocessing and (speech) signal preprocessing. They are in separate folders. They were made in google colab notebooks, with the main goal of training the practical knowledge of Natural Language Processing and Speech Processing. These projects could be updated soon.

## Description

### Text preprocessing project
This project refers to text normalization in the NLP pipeline. Tasks such as lemmatization, POS tagging, lowercasing and removing punctuation, tokenization and removing stop words were applied to text in portuguese and in english. This was done with pandas and spaCy libraries.

**Portuguese sentences (10):**
1. "Vou só ali ao café da esquina pedir uma bica e comer um pastel de nata antes que comece a chover.",
2. "Se fores ao supermercado, traz um pacote de miolo de noz e não te esqueças de meter a moeda no carrinho."
3. "Fiquei imenso tempo na paragem à espera do autocarro, mas ele acabou por vir completamente cheio."
4. "O miúdo mais novo passou o fim de semana todo a jogar consola e agora não quer fazer os trabalhos de casa."
5. "Estou a pensar seriamente em tirar uns dias de férias no Algarve para aproveitar o calor e a praia."
6. "Deixei as chaves de casa em cima da cómoda do quarto, podes ir buscá-las por favor?"
7. "Ontem fomos jantar fora e comemos um bacalhau à Brás que estava simplesmente divinal."
8. "Corta mas é o cabelo, que já estás com um ar muito desalinhado e a precisar de ir ao barbeiro."
9. "Fiquei farto de estar na fila das finanças, aquilo estava uma confusão pegada e o sistema ainda foi abaixo."
10. "Amanhã de manhã tenho de ir correr cedinho para compensar os excessos do fim de semana."

**English sentendes (10):**
1. "I love to read interesting books in the evening before going to sleep."
2. "The sun is shining brightly today, so we should go to the park."
3. "She works as a manager at a large international bank in Lisbon."
4. "We usually eat a delicious dinner together at seven o'clock."
5. "He lives in a big city because he likes the busy lifestyle."
6. "They play soccer with their friends every weekend at the local field."
7. "My dog always barks loudly whenever the mailman arrives at the door."
8. "The coffee is still very hot, so you should wait a few minutes."
9. "I want to learn English to get a better job in the future."
10. "Drinking enough water every day is extremely important for your health.

## Signal preprocessing project
For this project, were recorded five portuguese sentences with a sample rate of 48kHz and a bit depth of 24bit, in stereo. It was recorded in `.wav` file. To preprocess the audio signal, it was used the librosa library, as well as the matplotlib, numpy, pandas, glob, and IPython libraries.

The portuguese sentences list follow below:

- `frase1_pt.wav` - "O vento forte cortou o silêncio da noite fria."
- `frase2_pt.wav` - "Aquela velha ponte de pedra ruiu com a chuva de ontem."
- `frase3_pt.wav` - "O rapaz comprou pão fresco e fruta na praça central."
- `frase4_pt.wav` - "Todos os fins de semana, o meu avô caminha junto ao mar."
- `frase5_pt.wav` - "Deixei as chaves do carro em cima da mesa da cozinha."

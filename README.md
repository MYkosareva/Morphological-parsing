# Морфологический анализатор.  Morphological analyzer
**Цель проекта ** - создание морфологического анализатора для `русского языка`, без использования готовых решений (mystem, pymorphy, etc.).

Морфологический анализатор — программа для анализа морфологии слова, которая выявляет морфемы любого текста.

**Задача**: Лемматизировать текст (привести к словарной форме) и приписать леммам частеречные теги. Для решения задачи нельзя использовать существующие морфологические анализаторы (mystem, pymorphy и т.п.).

**Ввод**: предложения вида "токен1 токен2 ... токенN" с расставленными знаками препинания, разделенные переносом строки. Из знаков препинания в предложениях могут содержаться только запятая, точка, вопросительный и восклицательный знаки.

**Вывод**: для каждого предложения из входных данных вывод в виде "токен1{лемма1=тег1} токен2{лемма2= тег2} ... токенN{леммаN=тегN}" без исходных знаков препинания. Разделитель между токенами -- пробельный символ.

---------------------------------

**Target** of this project is create morph analyzer for `Russian language` without using existing frameworks (mystem, pymorphy, etc.).

A morphological analyzer is a program for analyzing the morphology of an input word, it detects morphemes of any text.

**Task**: Lemmatize the text (reduce it to a dictionary form) and assign part-of-speech tags to lemmas. You cannot use existing morphological analyzers (mystem, pymorphy, etc.) to solve the problem.

**Input**: sentences like "token1 token2 ... tokenN" with punctuation marks, separated by line breaks. Of the punctuation marks in sentences, only a comma, a period, a question mark, and an exclamation point can be contained.

**Output**: for each sentence from the input, the output is "token1{lemma1=tag1} token2{lemma2= tag2} ... tokenN{lemmaN=tagN}" without the original punctuation marks. The separator between tokens is a space character.



| File | Description |
| --- | --- |
| Morph_analyzer.ipynb | Морфологический анализатор для русского языка. В качестве исходного словаря используется "Морфологический словарь русского языка, GNU FDL 2012" (https://morfologija.ru/словоформа/)

Morphological analyzer for the Russian language. The "Morphological Dictionary of the Russian Language, GNU FDL 2012" is used as the source dictionary. (https://morfologija.ru/словоформа/) |

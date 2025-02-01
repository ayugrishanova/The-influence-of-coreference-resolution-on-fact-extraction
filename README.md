# The-influence-of-coreference-resolution-on-fact-extraction
# Влияние разрешения кореференции на задачу извлечения фактов из текстов разной сферы функционирования

В нашей работы мы проверяем, как разрешение кореференции влияет на задачу автоматического создания сводки (summary) из набора документов, которая отвечает на запрос конкретного пользователя. Мы применяем метод QF-MDS, предложенный в работе [Lamsiyah et al. 2021], на русскоязычных данных. Для этого мы создали корпус, аналогичный датасетам DUC 2005-2007 [Dang 2005], [Dang 2006], [Dang 2007]. 

Мы отобрали 25 вопросов, классифицированных учебником [Вигасин и др. 2023] как “Проверь себя”, и собрали для каждого из них по 4 развернутых ответа, написанных пользователями Интернета. Благодаря тому, что учебная программа является стандартизированной, содержание учебников разного авторства одинаково. Так, мы собрали тексты восьми разных учебников. Для того, чтобы еще более разнообразить коллекцию документов, была использована Википедия: мы вводили в поиск название главы (например, Афинская демократия при Перикле) и скачивали все статьи, удовлетворяющие поиску. После этого мы мануально перепроверяли, есть ли в статье информация, нужная для ответа на вопрос. 

Созданный нами датасет устроен следующим образом. Коллекция документов состоит из 8 учебников по 50-60 документов-глав и 62 документов из Википедии. В коллекции документов 46204 предложений, что сопоставимо с размерами коллекции документов датасетов DUC 2005-2007 [Dang 2007]. Всего в нашем датасете 25 вопросов-тем, и для каждого предложено по 4 “Золотые” сводки.

---

# The influence of coreference resolution on fact extraction

This is the repository for my 2024 term paper.
In my work, I check how the resolution of the coreference affects the task of automatically creating a summary from a set of documents that responds to a specific user's request. I apply the QF-MDS method proposed in [Lamsiyah et al. 2021] on the Russian data. To do this, I have created a corpus similar to the DUC 2005-2007 datasets [Dang 2005], [Dang 2006], [Dang 2007]. 

I selected 25 questions classified by the textbook [Vigasin et al. 2023] as “Test yourself”, and collected 4 detailed answers written by Internet users for each of them. Due to the fact that the curriculum is standardized, the content of textbooks of different authorship is the same. So, I have collected the texts of eight different textbooks. In order to further diversify the collection of documents, Wikipedia was used: I entered the chapter title into the search (for example, Athenian Democracy under Pericles) and downloaded all the articles that satisfied the search. After that, I manually rechecked whether the article contains the information necessary to answer the question. 

The dataset I created is arranged as follows. The document collection consists of 8 textbooks, 50-60 chapter documents each, and 62 Wikipedia documents. There are 46,204 sentences in the document collection, which is comparable to the size of the collection of DUC 2005-2007 dataset documents [Dang 2007]. In total, there are 25 question-topics in our dataset, and 4 “Golden” summaries are offered for each. 

This repository contains the generated summaries for each question and the term paper.

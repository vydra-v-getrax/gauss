# Разработка метода разложения векторов эмбеддингов с использованием гауссовской смеси

### Abstract
Static embeddings represent connection between words, but high dimension of the vector spaces complicates interpretation of the encoded semantic relations. In this paper, we introduce a method for vector space decomposition using Gaussian mixture models, which create interpretable topic clusters of words and allow to analyze the obtained components. To assess the method, we used pretrained Word2Vec models. Gaussian mixtures provided a plausible space decomposition where the components were close to human judgment. The analysis included visualization of components on a plane, comparison of the resulting gaussians covariance matrices and the rating of the dimensions by their variance. It reveals that Gaussian mixtures are an effective instrument for building interpretable semantic components as it allowed us to obtain a set of interpretable features which could describe the lexical relations. The question of scaling the approach, though, remains open. 

### Абстракт
Статические векторы отражают связи между словами, однако высокая размерность этих пространств затрудняет непосредственную интерпретацию закодированных в них семантических отношений. В работе предлагается метод интерпретации пространства, образуемого векторами эмбеддингов слов с использованием моделей Гауссовых смесей, которые строят интерпретируемые тематические кластеры слов и позволяют анализировать полученные компоненты. 
Для оценки использовались предобученные вектора Word2Vec. Модели Гауссовской смеси позволили получить близкое к интроспективному деление пространства на компоненты. Для анализа использовалось визуализация компонент на плоскости, анализ матриц ковариации полученных гауссиан и рейтингa измерений на основе дисперсии. В результате удалось построить смежные семантические компоненты и найти набор интерпретируемых признаков, которые в отдельных случаях правдоподобно описывали лексические отношения, но вопрос масштабирования подхода остался открытым.

[Основной код экспериментов](<https://github.com/vydra-v-getrax/gauss/Интерпретация векторов Гауссовская смесь.ipynb>)

[Ссылка на данные](https://drive.google.com/drive/folders/1Us4Q0g2V8Sf8R8VAmjbOPnzefmWS6Ul8?usp=sharing)

---
annotation-target: "[[SL_book.pdf]]"
---
## 3.1.1估计参数

>%%
>```annotation-json
>{"created":"2024-05-28T03:56:13.145Z","text":"观测值每一点与回归方程的值相减","updated":"2024-05-28T03:56:13.145Z","document":{"title":"SL_book.pdf","link":[{"href":"urn:x-pdf:3029de7deab3261f6aa7602c1fc92a94"},{"href":"vault:/book/SL_book.pdf"}],"documentFingerprint":"3029de7deab3261f6aa7602c1fc92a94"},"uri":"vault:/book/SL_book.pdf","target":[{"source":"vault:/book/SL_book.pdf","selector":[{"type":"TextPositionSelector","start":150070,"end":150142},{"type":"TextQuoteSelector","exact":"RSS = (y1 − ˆβ0 − ˆβ1x1)2 +(y2 − ˆβ0 − ˆβ1x2)2 +···+(yn − ˆβ0 − ˆβ1xn)2.","prefix":"22 + ···+ e2n,or equivalently as","suffix":" (3.3)The least squares approach"}]}]}
>```
>%%
>*%%PREFIX%%22 + ···+ e2n,or equivalently as%%HIGHLIGHT%% ==RSS = (y1 − ˆβ0 − ˆβ1x1)2 +(y2 − ˆβ0 − ˆβ1x2)2 +···+(yn − ˆβ0 − ˆβ1xn)2.== %%POSTFIX%%(3.3)The least squares approach*
>%%LINK%%[[#^ldlusao1rfa|show annotation]]
>%%COMMENT%%
>观测值每一点与回归方程的值相减
>%%TAGS%%
>#RSS（残差平方和）
^ldlusao1rfa



>%%
>```annotation-json
>{"text":"对RSS的表达式分别对β1和β2求偏导，让两个式子分别等于0，联立两个式子就可以估计得到β1和β2","target":[{"source":"vault:/book/SL_book.pdf","selector":[{"type":"TextPositionSelector","start":150216,"end":150272},{"type":"TextQuoteSelector","exact":"Usingsome calculus, one can show that the minimizers are","prefix":"β0 and ˆβ1 to minimize the RSS.","suffix":"ˆβ1 =∑ni=1(xi −  ̄x)(yi −  ̄y)∑n"}]}],"created":"2024-05-29T04:52:13.479Z","updated":"2024-05-29T04:52:13.479Z","document":{"title":"SL_book.pdf","link":[{"href":"urn:x-pdf:3029de7deab3261f6aa7602c1fc92a94"},{"href":"vault:/book/SL_book.pdf"}],"documentFingerprint":"3029de7deab3261f6aa7602c1fc92a94"},"uri":"vault:/book/SL_book.pdf"}
>```
>%%
>*%%PREFIX%%β0 and ˆβ1 to minimize the RSS.%%HIGHLIGHT%% ==Usingsome calculus, one can show that the minimizers are== %%POSTFIX%%ˆβ1 =∑ni=1(xi −  ̄x)(yi −  ̄y)∑n*
>%%LINK%%[[#^vg4t9uoo72|show annotation]]
>%%COMMENT%%
>对RSS的表达式分别对β1和β2求偏导，让两个式子分别等于0，联立两个式子就可以估计得到β1和β2
>%%TAGS%%
>#最小二乘法
^vg4t9uoo72

## 3.1.2评估系数估计的准确性


>%%
>```annotation-json
>{"created":"2024-05-29T05:12:05.629Z","updated":"2024-05-29T05:12:05.629Z","document":{"title":"SL_book.pdf","link":[{"href":"urn:x-pdf:3029de7deab3261f6aa7602c1fc92a94"},{"href":"vault:/book/SL_book.pdf"}],"documentFingerprint":"3029de7deab3261f6aa7602c1fc92a94"},"uri":"vault:/book/SL_book.pdf","target":[{"source":"vault:/book/SL_book.pdf","selector":[{"type":"TextPositionSelector","start":152117,"end":152177},{"type":"TextQuoteSelector","exact":"We typically assume that the error term is independent of X.","prefix":" there may be measurementerror. ","suffix":"The model given by (3.5) defines"}]}]}
>```
>%%
>*%%PREFIX%%there may be measurementerror.%%HIGHLIGHT%% ==We typically assume that the error term is independent of X.== %%POSTFIX%%The model given by (3.5) defines*
>%%LINK%%[[#^jzbf0ktagl|show annotation]]
>%%COMMENT%%
>
>%%TAGS%%
>
^jzbf0ktagl


>%%
>```annotation-json
>{"text":"[正态分布](https://zh.wikipedia.org/zh-cn/正态分布#)","target":[{"source":"vault:/book/SL_book.pdf","selector":[{"type":"TextPositionSelector","start":153358,"end":153414},{"type":"TextQuoteSelector","exact":"\"was generated from a normal distribution with mean zero","prefix":"odelY = 2 + 3 X + \", (3.6)where","suffix":". Thered line in the left-hand p"}]}],"created":"2024-05-29T05:18:44.524Z","updated":"2024-05-29T05:18:44.524Z","document":{"title":"SL_book.pdf","link":[{"href":"urn:x-pdf:3029de7deab3261f6aa7602c1fc92a94"},{"href":"vault:/book/SL_book.pdf"}],"documentFingerprint":"3029de7deab3261f6aa7602c1fc92a94"},"uri":"vault:/book/SL_book.pdf"}
>```
>%%
>*%%PREFIX%%odelY = 2 + 3 X + ", (3.6)where%%HIGHLIGHT%% =="was generated from a normal distribution with mean zero== %%POSTFIX%%. Thered line in the left-hand p*
>%%LINK%%[[#^s41w3u9cqol|show annotation]]
>%%COMMENT%%
>[正态分布](https://zh.wikipedia.org/zh-cn/正态分布#)
>%%TAGS%%
>#正态分布
^s41w3u9cqol


>%%
>```annotation-json
>{"created":"2024-05-29T05:30:53.306Z","updated":"2024-05-29T05:30:53.306Z","document":{"title":"SL_book.pdf","link":[{"href":"urn:x-pdf:3029de7deab3261f6aa7602c1fc92a94"},{"href":"vault:/book/SL_book.pdf"}],"documentFingerprint":"3029de7deab3261f6aa7602c1fc92a94"},"uri":"vault:/book/SL_book.pdf","target":[{"source":"vault:/book/SL_book.pdf","selector":[{"type":"TextPositionSelector","start":153746,"end":153926},{"type":"TextQuoteSelector","exact":"In other words, in real applications,we have access to a set of observations from which we can compute theleast squares line; however, the population regression line is unobserved.","prefix":"cient estimates given in (3.4). ","suffix":"In the right-hand panel of Figur"}]}]}
>```
>%%
>*%%PREFIX%%cient estimates given in (3.4).%%HIGHLIGHT%% ==In other words, in real applications,we have access to a set of observations from which we can compute theleast squares line; however, the population regression line is unobserved.== %%POSTFIX%%In the right-hand panel of Figur*
>%%LINK%%[[#^0qu1dl86h4j|show annotation]]
>%%COMMENT%%
>
>%%TAGS%%
>
^0qu1dl86h4j

### 真实的回归线和通过最小二乘法得到的曲线之间有什么不同的地方吗？


>%%
>```annotation-json
>{"created":"2024-05-29T05:55:39.896Z","text":"从根本上来说，这两条线的概念是使用样本信息来估计大量人群特征的标准统计方法的自然延伸。","updated":"2024-05-29T05:55:39.896Z","document":{"title":"SL_book.pdf","link":[{"href":"urn:x-pdf:3029de7deab3261f6aa7602c1fc92a94"},{"href":"vault:/book/SL_book.pdf"}],"documentFingerprint":"3029de7deab3261f6aa7602c1fc92a94"},"uri":"vault:/book/SL_book.pdf","target":[{"source":"vault:/book/SL_book.pdf","selector":[{"type":"TextPositionSelector","start":154733,"end":154922},{"type":"TextQuoteSelector","exact":" Fundamentally, theconcept of these two lines is a natural extension of the standard statisticalapproach of using information from a sample to estimate characteristics of alarge population.","prefix":" the predictor and the response?","suffix":" For example, suppose that we ar"}]}]}
>```
>%%
>*%%PREFIX%%the predictor and the response?%%HIGHLIGHT%% ==Fundamentally, theconcept of these two lines is a natural extension of the standard statisticalapproach of using information from a sample to estimate characteristics of alarge population.== %%POSTFIX%%For example, suppose that we ar*
>%%LINK%%[[#^3cmhgea4cse|show annotation]]
>%%COMMENT%%
>从根本上来说，这两条线的概念是使用样本信息来估计大量人群特征的标准统计方法的自然延伸。
>%%TAGS%%
>#estimate（估计）
^3cmhgea4cse

举个例子来说：
- 我们对一个数据集的总体样本感兴趣，可是我们无法得到；但是我们有一系列观测量：$y_1,y_2,y_3,...,y_n$ ，这样我们就可以得到样本均值 $\bar{y}=\frac{1}{n}\sum_{i=0}^{n} y_i$，可以让样本均值等于总体均值，虽然他们之间存在不同，但是这是一个合理的估计。
- 用上面的$\beta_0$和$\beta_1$来说，我们无法精准地得到确切的值，但是我们可以通过最小二乘法得到$\hat{\beta_0}$和$\hat{\beta_1}$来合理估计$\beta_0$和$\beta_1$。





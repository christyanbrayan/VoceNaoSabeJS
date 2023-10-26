# [Livro 5 - Async & Performance](../05-async-and-performance/)

## Índice

* [Introdução](foreword.md)
* [Capítulo 1: Assíncronia: Agora & Depois](ch1.md)
	* [Um Programa em Pedaços](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch1.html#um-programa-em-peda%C3%A7os)
	* [Loop de Eventos](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch1.html#loop-de-eventos)
	* [Threading Paralelo](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch1.html#threading-paralelo)
	* [Concorrência](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch1.html#concorr%C3%AAncia)
	* [Fila de Tarefas](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch1.html#fila-de-tarefas)
	* [Ordenamento de Instruções](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch1.html#ordenamento-de-instru%C3%A7%C3%B5es)
* [Capítulo 2: Callbacks](ch2.md)
	* [Continuações](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch2.html#continua%C3%A7%C3%B5es)
	* [Cérebro Sequencial](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch2.html#c%C3%A9rebro-sequencial)
	* [Trust Issues](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch2.html#trust-issues)
	* [Tentando Salvar os Callbacks](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch2.html#trying-to-save-callbacks)
* [Capítulo 3: Promessas](ch3.md)
	* [O que É Uma Promessa?](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch3.html#what-is-a-promise)
	* [Thenable Duck-Typing](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch3.html#thenable-duck-typing)
	* [Promise Trust](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch3.html#promise-trust)
	* [Chain Flow](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch3.html#chain-flow)
	* [Error Handling](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch3.html#error-handling)
	* [Padrões de Promessas](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch3.html#promise-patterns)
	* [Recaptuando a API das Promessas](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch3.html#promise-api-recap)
	* [Limitações de Promessas](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch3.html#promise-limitations)
* [Capítulo 4: Generators](ch4.md)
	* [Desmembrando o Rodar-até-acabar](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch4.html#desmembrando-o-rodar-at%C3%A9-acabar)
	* [Generator'ing Values](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch4.html#generatoring-values)
	* [Iterating Generators Asynchronously](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch4.html#iterating-generators-asynchronously)
	* [Generators + Promises](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch4.html#generators--promises)
	* [Generator Delegation](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch4.html#generator-delegation)
	* [Generator Concurrency](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch4.html#generator-concurrency)
	* [Thunks](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch4.html#thunks)
	* [Pre-ES6 Generators](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch4.html#pre-es6-generators)
* [Capítulo 5: Performance do Programa](ch5.md)
	* [Web Workers](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch5.html#web-workers)
	* [SIMD](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch5.html#simd)
	* [asm.js](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch5.html#asmjs)
* [Capítulo 6: Benchmarking & Tuning](ch6.md)
	* [Benchmarking](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch6.html#benchmarking)
	* [Contexto É Tudo](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch6.html#context-is-king)
	* [jsPerf.com](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch6.html#jsperfcom)
	* [Escrevendo Testes com Qualidade](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch6.html#writing-good-tests)
	* [Microperformance](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch6.html#microperformance)
	* [Tail Call Optimization (TCO)](https://christyanbrayan.github.io/VoceNaoSabeJS/05-async-and-performance/ch6.html#tail-call-optimization-tco)
* [Apêndice A: Biblioteca de *assinquência*](apA.md)
* [Apêndice B: Padrões Avançados de Async](apB.md)
* [Apêndice C: Agradecimentos](apC.md)
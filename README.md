_a template on which this thesis is written can be found [here](https://github.com/Uko/thesis-template)_
[![Build Status](https://travis-ci.org/Uko/metamodels-thesis.png?branch=master)](https://travis-ci.org/Uko/metamodels-thesis) Магістерська робота по метамоделях / Metamodels master's thesis
=============================================================================================================================================================================================

Вступ:
------
Метамоделювання було створено, щоб дозволити розглядати програми на більш високому рівні абстракції, ніж це дозволяють поточні мови програмування. Основна ідея полягає в тому, що хтось визначає високорівневу модель рішення, описує, як перетворити це рішення в програму для даної мови, а потім автоматично генерує вихідний код. В ідеалі такий же підхід дозволяє взяти існуючу програму, автоматично отримати абстрактну модель з неї, вручну розширити або поліпшити модель і згенерувати нову програму, можливо, на новій мові програмування (round-trip engineering). Такий підхід був би дуже цікавим для організацій, що мають програми написані на старих технологіях (наприклад, Cobol) і хочуть перенести їх на більш сучасні (наприклад, Java). Команда RMod вже має інструменти, які можуть приймати програми (написані на C, Java, Smalltalk, і т.д.) в якості вхідних даних і продукувати з них метамоделі.

Тим не менш, чорт сидить в деталях, в даному випадку, для зворотньої розробки існуючої програми, щоб мати можливість відновити її потім, треба тримати багато деталей про цю програму. Ця потреба, звичайно, не сумісна з ідеєю абстрагування моделі цієї програми. Тому потрібно, бути в змозі створити абстрактну модель програми, але, в той же час, створити дуже детальну модель тієї ж програми і таким чином, мати можливість працювати на двох рівнях абстракції одночасно.

Abstract:
---------
Metamodelling was created to allow reasonning on programs at a higher level of abstraction than what current programming languages allow. The idea is that one defines a high level model of a solution, describes how to transform this solution into a program for a given language and then automatically generates the source code. Ideally the same kind of approach allows to take an existing program, automatically extract an abstract model from it, manually extend or improve the model and regenerate a new program, possibly in a new programming language (round-trip engineering). This approach would be very interesting for organizations that have programs in old technologies (e.g. Cobol) and want to migrate them towards more modern ones (e.g. Java). RMod team already has tools that can take programs (written in C, Java, Smalltalk, etc.) as input and produce metamodels as output.

However, the Devil is in the details, in this case, for reverse engineering an existing program to be able to regenerate it afterward, one needs to keep many details on that program. This, of course, is not compatible with the idea of abstracting a model of this program. One needs therefore to be able to create an abstract model of a program but, at the same time, to create a very detailed model of the same program so as to be able to work at two levels of abstraction at the same time.
---
title: Поточная раскладка CSS
slug: Web/CSS/CSS_Flow_Layout
tags:
  - CSS
  - Раскладка
  - Руководство
  - поток
  - поточная раскладка
translation_of: Web/CSS/CSS_Flow_Layout
---
{{CSSRef}}

_Нормальный поток (normal flow)_ или поточная раскладка (flow layout), это способ отображения блочных (block) и строчных (inline) элементов на странице. Сначала раскладка этих элементов происходит согласно правилам потока, после чего в неё могут быть внесены изменения, например, относительное позиционирование.

По сути поток представляется собой набор сущностей, которые работают вместе и знают друг о друге. Когда некоторая сущность _вынимается из потока (out of flow)_, то она работает независимо.

В нормальном потоке **строчные (inline)** элементы отображаются в направлении строки (inline direction), то есть в том же направлении, как идут слова в предложении в соответствии с режимом письма ([writing mode](/ru/docs/Web/CSS/CSS_Writing_Modes)) документа. **Блочные (block)** элементы отображаются один за другим, также как параграфы в соответствии с режимом письма документа. Поэтому в английском языке строчные элементы отображаются один за другим, начиная слева, а блочные элементы выкладываются на странице сверху вниз.

## Пример

Следующий пример показывает боксы уровня блока (block level) и уровня строки (inline level). Боксы уровня блока участвуют в блочном контексте форматирования, а боксы уровня строки в строчном контексте форматирования.

Два элемента параграфа с зелёной границей создают боксы уровня блока, отображающиеся один под другим.

Первое предложение также содержит элемент span с голубым фоном. Он создаёт бокс уровня строки и, следовательно, размещается внутри предложения.

{{EmbedGHLiveSample("css-examples/layout/normal-flow.html", '100%', 720)}}

## Руководства

- Блочная и строчная раскладки в нормальном потоке ([Block and Inline Layout in Normal Flow](/ru/docs/Web/CSS/CSS_Flow_Layout/Block_and_Inline_Layout_in_Normal_Flow)).
- В потоке и вне потока ([In Flow and Out of Flow](/ru/docs/Web/CSS/CSS_Flow_Layout/In_Flow_and_Out_of_Flow)).
- Объяснение контекстов форматирования ([Formatting Contexts Explained](/ru/docs/Web/CSS/CSS_Flow_Layout/Formatting_Contexts_Explained)).
- Поточная раскладка и режимы письма ([Flow Layout and Writing Modes](/ru/docs/Web/CSS/CSS_Flow_Layout/Flow_Layout_and_Writing_Modes)).
- Поточная раскладка и переполнение ([Flow Layout and Overflow](/ru/docs/Web/CSS/CSS_Flow_Layout/Flow_Layout_and_Overflow)).

## Ссылки

### Записи глоссария

- {{Glossary("Block/CSS", "Block (CSS)")}}

1.  [**CSS**](/ru/docs/Web/CSS)
2.  [**CSS Reference**](/ru/docs/Web/CSS/Reference)
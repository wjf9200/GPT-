图片转为latex指令：
```latex
\textbf{LaTeX 转换要求：}
请将图片中的内容转换为 LaTeX，要求：
\begin{enumerate}
    \item 只输出 LaTeX 代码，不要解释文字。
    \item 公式统一使用 $\backslash label\{\}$ 标签，不使用 $\backslash tag\{\}$。
    \item 独立公式使用：
    \begin{equation}
    \label{eq:自定义英文标签}
    ...
    \end{equation}
    \item 行内公式使用 $...$。
    \item 如果行内公式中出现求和符号、极限符号、积分符号等需要上下标显示在正上方/正下方，统一添加 $\backslash limits$，例如：
    \[
    \sum\limits_{|\alpha|\leq k}
    \]
    而不是：
    \[
    \sum_{|\alpha|\leq k}
    \]
    \item 保持原文内容、公式、符号完全一致，不自行改写、补充或删减。
    \item 公式编号不要保留图片中的编号，统一使用 $\backslash label$ 管理。
    \item 如果图片中有标题（如“定理”“定义”“证明”等），保留并转换为 LaTeX 文本。
\end{enumerate}
```

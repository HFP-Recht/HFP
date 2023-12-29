$$
\begin{tikzpicture}[auto, node distance=2cm,>=Latex]

% Define styles
\tikzstyle{box} = [rectangle, rounded corners, minimum width=3cm, minimum height=1cm, draw=black, text centered]
\tikzstyle{arrow} = [->,thick]

% Nodes
\node[box] (seller) {Seller (1)};
\node[box, right=of seller] (buyer) {Buyer (2)};

% Arrows
\draw [arrow] (seller) -- node {3. Delivery of Goods} (buyer);
\draw [arrow] (buyer) |- ++(0,-1) -| node[near start] {4. Payment of Price} (seller);

\end{tikzpicture}
$$
# time-span

~~~~~ sh
npm install e53e04ac/time-span
~~~~~

~~~~~ mjs
import { TimeSpan } from 'e53e04ac/time-span';
~~~~~

~~~~~ mermaid
graph LR;
  A(["time-span"]);
  B0(["e53e04ac/base"]);
  B1(["e53e04ac/hold"]);
  C0(["@types/node"]);
  click B0 href "https://github.com/e53e04ac/base";
  click B1 href "https://github.com/e53e04ac/hold";
  subgraph "e53e04ac/time-span";
    A;
  end;
  subgraph "dependencies";
    B0 --import--> A;
    B1 --import--> A;
  end;
  subgraph "devDependencies";
    C0 --import--> A;
  end;
~~~~~

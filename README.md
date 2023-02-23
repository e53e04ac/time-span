# time-span

~~~~~ sh
npm install e53e04ac/time-span
~~~~~

~~~~~ mjs
import { TimeSpan } from 'e53e04ac/time-span';
~~~~~

~~~~~ mermaid
graph RL;
  A(["package.json"]);
  subgraph "dependencies";
    B_0(["e53e04ac/base"]);
    B_1(["e53e04ac/hold"]);
  end;
  subgraph "devDependencies";
    B_2(["@types/node"]);
  end;
  A ----> B_0;
  A ----> B_1;
  A ----> B_2;
  click B_0 "https://github.com/e53e04ac/base/tree/fc0fe75d4737062206ea1b99def2b1b2df6b99fa";
  click B_1 "https://github.com/e53e04ac/hold/tree/443c2e801bbe20409c761994a91fa88fb6044602";
  click B_2 "https://www.npmjs.com/package/@types/node/v/18.14.1";
~~~~~

~~~~~ mermaid
graph RL;
  subgraph "e53e04ac/time-span";
    E_0(["TimeSpan"]);
  end;
  M(["index.mjs"])
  subgraph "base";
    I_0_0(["Base"]);
  end;
  subgraph "hold";
    I_1_0(["hold"]);
    I_1_1(["unwrap"]);
  end;
  M ----> I_0_0;
  M ----> I_1_0;
  M ----> I_1_1;
  E_0 ----> M;
~~~~~

~~~~~ mermaid
graph RL;
  subgraph "e53e04ac/time-span";
    E_0(["namespace TimeSpan"]);
    E_1(["type TimeSpan"]);
    E_2(["const TimeSpan"]);
  end;
  M(["index.d.ts"])
  subgraph "base";
    I_0_0(["Base"]);
  end;
  subgraph "hold";
    I_1_0(["Get"]);
    I_1_1(["ValueOrGet"]);
  end;
  M ----> I_0_0;
  M ----> I_1_0;
  M ----> I_1_1;
  E_0 ----> M;
  E_1 ----> M;
  E_2 ----> M;
~~~~~

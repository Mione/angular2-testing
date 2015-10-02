1. Daca aveti node instalat, treceti la 2, daca nu: https://docs.npmjs.com/getting-started/installing-node
2. Rulati urmatoarea comanda, o sa instaleze typescript-ul si niste definitii pentru el, precum si un server light-weight pentru testat <code>npm install -g typescript tsd live-server</code> 
3. Trebuie instalate dependintele din package.json. <code>npm install</code>
4. Compilam typescript-ul <code>tsc -p src -w</code>, din root-ul aplicatiei, nu din src
5. Deschidem un nou terminal, tot in root.
5. Rulam serverul <code> live-server --port=8107 </code> portul e inlocuibil cu orice

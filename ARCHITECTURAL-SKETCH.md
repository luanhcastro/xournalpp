## ARCHITECTURAL SKETCH (Esboço de arquitetura)

O projeto conta com novas funcionalidades que incluem tanto abrir automaticamente o pdf relacionado a um arquivo de anotação, quanto a abrir um arquivo de anotação relacionado a um pdf.
A classe a seguir pode ser tanto um arquivo pdf quanto um de anotação.

### Classe

<img src="images/fileClass.png" width=100% title="File Class"/>

### fluxos

Existem 3 fluxos possíveis:

1. O arquivo de anotação ou pdf relacionado é encontrado.

<img src="images/sequence1.png" width=100% title="Sequence diagram 1"/>

2. Uma lista de arquivos similares é fornecida ao usuário e ele escolhe qual deseja abrir.
   
<img src="images/sequence2.png" width=100% title="Sequence diagram 2"/>

3. Nenhum arquivo válido foi encontrado e o usuário é alertado.
   
<img src="images/sequence3.png" width=100% title="Sequence diagram 3"/>

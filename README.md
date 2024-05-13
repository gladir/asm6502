# asm6502
Cette commande, écrit en Pascal (Turbo Pascal ou Free Pascal), permet de lancer le compilateur de langage de programmation assembleur pour les microprocesseur 6502.

<h3>Syntaxe</h3>

ASM6502 [options] src [options]

<h3>Paramètres</h3>

<table>
		<tr>
			<th>Nom</th>
			<th>Description</th>
		</tr>
		<tr>
			<td><i>src</i></td>
			<td>Ce paramètre permet d'indiquer le fichier source assembleur.</td>
		</tr>		
		<tr>
			<td><b>-E</b></td>
			<td>Ce paramètre permet d'indiquer qu'il faut afficher les erreurs à l'écran.</td>
		</tr>
		<tr>
			<td><b>-L</b></td>
			<td>Ce paramètre permet d'indiquer qu'il faut fabriquer un fichier de liste <i>src</i>.LIS</td>
		</tr>
		<tr>
			<td><b>-L</b>=<i>nom</i></td>
			<td>Ce paramètre permet d'indiquer qu'il faut fabriquer un fichier de liste <i>nom</i>.</td>
		</tr>
		<tr>
			<td><b>-O</b></td>
			<td>Ce paramètre permet d'indiquer qu'il faut fabrique un fichier objet de <i>src</i>.OBJ</td>
		</tr>
		<tr>
			<td><b>-O</b>=<i>nom</i></td>
			<td>Ce paramètre permet d'indiquer qu'il faut fabrique un fichier objet <i>nom</i>.</td>
		</tr>
		<tr>
			<td><b>-B</b></td>
			<td>Ce paramètre permet d'indiquer qu'il faut fabriquer un fichier binaire de <i>src</i>.BIN</td>
		</tr>
		<tr>
			<td><b>-B</b>=<i>nom</i></td> 
			<td>Ce paramètre permet d'indiquer qu'il faut fabriquer un fichier binaire <i>nom</i></td>
		</tr>
	</table>

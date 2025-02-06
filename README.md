# WinUtil_Cloud
Your go-to utility for optimizing and managing your Windows environment

ITALIAN

## WinUtil Cloud Versione All-in-One:

WinUtil (Windows Utility) è un'utility per l'ottimizzazione e la configurazione di sistemi Windows, pensato per semplificare e migliorare l'esperienza d'uso. In particolare, serve a migliorare le prestazioni del sistema, risolvere problemi e personalizzare l'ambiente software. Questa utility infatti facilita l'installazione di programmi, rimuove applicazioni inutili, offre regolazioni per il sistema e migliora la gestione degli aggiornamenti di Windows. E' apprezzata particolarmente dagli utenti che desiderano un'esperienza Windows più pulita e performante, poiché permette di eliminare software superflui mantenendo al contempo le funzionalità necessarie.
L'uso improprio di questa utility può interrompere la tua installazione, quindi fai attenzione perché non fornirò alcun aiuto o assistenza se ciò dovesse accadere!

Ecco una panoramica di come funziona e delle sue principali funzioni:

Installazione e avvio: Windows Utility è uno script PowerShell che richiede i permessi di amministratore per eseguire modifiche a livello di sistema.

Debloating: L'utility rimuove software preinstallato e applicazioni di sistema non necessarie, migliorando le prestazioni e liberando memoria. Questo processo è configurabile, per permettere agli utenti di selezionare quali elementi conservare.

Configurazioni avanzate: Include una serie di "tweak" per ottimizzare vari aspetti di Windows, come le impostazioni di privacy, le prestazioni, l'interfaccia utente e la velocità di avvio. È possibile attivare o disattivare queste configurazioni in base alle proprie esigenze.

Aggiornamenti e risoluzione dei problemi: Windows Utility offre strumenti per la gestione degli aggiornamenti di Windows, permettendo di controllare o ritardare aggiornamenti automatici e risolvere eventuali errori legati a questi. Inoltre, ha funzioni di diagnostica per risolvere problemi comuni del sistema.

Installazione di programmi: Consente l'installazione rapida di software selezionati, con una lista di programmi comunemente utilizzati che l'utente può scegliere di installare.

Per maggiori dettagli, controlla la home page: https://christitus.com/windows-tool/

Divertitevi ;-)

p.s. Ricorda che sei responsabile di ciò che stai facendo su Internet e anche se questo script esiste, potrebbe non essere legale nel tuo paese utilizzarlo.

L'UTILIZZO DEL SOFTWARE È A PROPRIO ESCLUSIVO RISCHIO E PERICOLO. IL SOFTWARE È FORNITO DAI DETENTORI DEL COPYRIGHT E DAI COLLABORATORI "COSÌ COM'È" E NON SI RICONOSCE ALCUNA ALTRA GARANZIA ESPRESSA O IMPLICITA, INCLUSE, A TITOLO ESEMPLIFICATIVO, GARANZIE IMPLICITE DI COMMERCIABILITÀ E IDONEITÀ PER UN FINE PARTICOLARE. IN NESSUN CASO IL PROPRIETARIO DEL COPYRIGHT O I RELATIVI COLLABORATORI POTRANNO ESSERE RITENUTI RESPONSABILI PER DANNI DIRETTI, INDIRETTI, INCIDENTALI, SPECIALI, PUNITIVI, O CONSEQUENZIALI (INCLUSI, A TITOLO ESEMPLIFICATIVO, DANNI DERIVANTI DALLA NECESSITÀ DI SOSTITUIRE BENI E SERVIZI, DANNI PER MANCATO UTILIZZO, PERDITA DI DATI O MANCATO GUADAGNO, INTERRUZIONE DELL'ATTIVITÀ), IMPUTABILI A QUALUNQUE CAUSA E INDIPENDENTEMENTE DALLA TEORIA DELLA RESPONSABILITÀ, SIA NELLE CONDIZIONI PREVISTE DAL CONTRATTO CHE IN CASO DI "STRICT LIABILITY", ERRORI (INCLUSI NEGLIGENZA O ALTRO), ILLECITO O ALTRO, DERIVANTI O COMUNQUE CORRELATI ALL'UTILIZZO DEL SOFTWARE, ANCHE QUALORA SIANO STATI INFORMATI DELLA POSSIBILITÀ DEL VERIFICARSI DI TALI DANNI.

Licenza MIT (Massachusetts Institute of Technology)

------------------------------------------------------------------------------------
ENGLISH

## WinUtil Cloud Version All-in-One:

WinUtil is your go-to utility for optimizing and managing your Windows environment. Whether you're an IT professional, power user, or regular user, WinUtil provides a comprehensive set of tools to enhance your Windows experience.
Misuse of this utility can break your install so please be careful and I do not provide any help or assistance should this happen!

NOTE: WinUtil is updated weekly as of the time of writing. Consequently, features and functionalities may evolve, and the documentation may not always reflect the most current images or information.

## Parts of Utility
There are four main parts of this utility but I can expand this to an infinite number of tabs if expansion is needed and will probably happen in the future. As of the writing of this article there is 4 main parts: install, debloat, features and old panels, and windows updates. Let me breakdown what each part does and what you should use.

### Install
The install is basically a better version of ninite that many people use. It leverages Microsoft's winget utility to not only install tons of software that you select with a check-mark, but also gives you the ability to upgrade all the software quickly. By using this utility you will save hours on the install, but also make it very easy to keep all your programs up to date.

### Debloat
Debloating windows is always a moving target and there are many utilities out there. Many of them are too heavy handed in my opinion. This takes a more minimal approach that should not damage your Windows install. At the top there are three buttons Desktop, Laptop, and Minimal. These are curated selections based on my recommendations

Desktop - This is for Desktops DUH, but it will disable features like power throttling and many services will be set to not auto start. This will give your desktop the best performance without any downside.

Laptop - This one is just like desktop but doesn't mess with power settings as we don't want to kill our laptops battery.

Minimal - This one will just do the absolute basic privacy / security settings. Very minor optimizations will also be made.

I must warn you to NOT use all the settings at once, or simple remove everything from the MS Store. Many times this will debloat the install but will BREAK the MS Store or uninstall any games / apps that were installed using it. This is why this option is never selected, but I left it there for those that really want to remove it. I personally do NOT recommend this, but I understand those that want to remove it.

Note: This part of the utility can break an install if used carelessly, but it does make a restore point so if you have a lot problems with it, you can use System Restore to rollback the changes or the Undo All option. THIS IS SOFTWARE IS PROVIDE WITHOUT ANY WARRANTY AND I AM NOT RESPONSIBLE FOR ANY MISUSE.

### Features and Legacy Win Panels
This tab makes it easier to enable built-in features that are off by default. Many new installs need these and I wanted to make it easier than going through and manually installing them one by one.

There is also the old school legacy panels that I use on a daily basis. I still find these to be more efficient than the new panels that Microsoft has put in Windows 10 and 11.

### Windows Updates
Windows updates set to defaults are crazy. They install and download at weird times and often update far too much. I give 2 options my recommended one that only installs security updates and allowing features updates after they have been proven over 1 year.

However, there is a disable all button. I do NOT recommend doing this, but is there for people that have specific software that they don't update and don't want their windows install changing at all. This is NOT secure, but often more stable and why you'd want to do something like this.

For more details, check Homepage: https://christitus.com/windows-tool/

Enjoy ;-)

p.s. Remember that you are responsible for what you are doing on the Internet and even if this script exists, it may not be legal in your country to use it.

USE OF THE SOFTWARE IS AT YOUR OWN RISK. THE SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND COLLABORATORS "AS IS" AND THERE IS NO EXPRESS OR IMPLIED WARRANTY, INCLUDING, BUT NOT LIMITED TO, IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR. IN NO EVENT SHALL THE OWNER OF THE COPYRIGHT OR ITS COLLABORATORS BE HELD LIABLE FOR DIRECT, INDIRECT, INCIDENTAL, SPECIAL, PUNITIVE, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, DAMAGES, DAMAGES ARISING FROM THE LOSS OF DATA OR FAILURE TO EARN, INTERRUPTION OF BUSINESS), CAUSED BY ANY CAUSE AND REGARDLESS OF THE THEORY OF LIABILITY, BOTH IN THE CONDITIONS PROVIDED BY THE CONTRACT AND IN CASE OF "STRICT LIABILITY", ERRORS (INCLUDING NEGLIGENCE OR OTHERWISE), ARISING OR OTHERWISE RELATED TO YOUR USE OF THE SOFTWARE, EVEN IF YOU HAVE BEEN INFORMED OF THE POSSIBILITY OF SUCH DAMAGES.

MIT (Massachusetts Institute of Technology) licence

## Info

**Tutor:** Cristofer Villani.

Questo tutorato ha lo scopo principale di aiutarvi a prepararvi con costanza all'esame di Algebra I, in un momento in cui avete altre lezioni e 
impegni vari. Per il momento, è così strutturato: ogni settimana, metterò *qui* degli esercizi da fare per il prossimo incontro di tutorato.
Siete fortemente invitati a farne almeno alcuni, e a consegnarmeli (via mail, a *c.villani4*_at_studenti.etc.) entro il giorno prima del successivo
incontro. In questo modo,

- potrete partecipare attivamente alla correzione;
- potrò darvi dei feedback sulla *scrittura* delle soluzioni, che è tanto importante quanto le soluzioni stesse.

## Prossimo incontro

**Data e Aula:** I tutorati di questa settimana saranno, rispettivamente, **mercoledì 22 maggio 11-13** in **aula E1** e **venerdì 24 maggio 14-16** in **aula N1**. Aggiungerò esercizi per venerdì entro domani mattina alle 10.

**Teoria:** rivedere le lezioni 26-33.

## Esercizi passati

**Tutorato 1:** 
- dal libro, es. 10, 12, 16, 17, 19;
- mostrate che $\mathbb{Z}/d$, per $d$ dispari, non è isomorfo al gruppo di automorfismi $\text{Aut}(G)$ di alcun gruppo finito $G$;
- sia $G$ un gruppo che agisce *transitivamente* su un insieme $X$ (i.e., c'è una sola orbita), e sia $N$ un sottogruppo normale di $G$. Dimostrate che
  - se $x,y\in X$, $\text{stab}_G(x)$ e $\text{stab}_G(y)$ sono coniugati;
  - l'azione di $N$ su $X$ non è necessariamente transitiva;
  - le orbite dell'azione di $N$ su $X$ hanno tutte la stessa cardinalità. 

**Tutorato 2:** 
- Dal libro, es. 28, 29, 110, 115. 
- Sia $G=\text{GL}(2,\mathbb{F}_3)$.
  - Calcolate $|G|$.
  - Determinate $\text{Z}(G)$.
  - ($\star$) Mostrate che $G/\text{Z}(G)\simeq S_4$.
- Per $H,K < G$, un _laterale doppio_ di $H$ e $K$ è un sottoinsieme della forma $HgK=\lbrace hgk\mid h\in H, k\in K\rbrace$, per qualche $g\in G$. Se $H$ e $K$ sono finiti, e $g\in G$, mostrate che vale $|HgK|=|H|\cdot|K|/|K\cap g^{-1}Hg|$.
- Sia $G$ un gruppo finito, e sia $p$ un primo tale che $p$ divide $|G|$. Mostrate che il numero di sottogruppi di ordine $p$ in $G$ è congruo a $1$ modulo $p$. _Hint: può essere utile ripartire dalla dimostrazione del teorema di Cauchy via azione di_ $\mathbb{Z}/p$.
- Sia $G$ un gruppo finito, e sia $H < G$. Consideriamo l’azione di $G$ per moltiplicazione (a sinistra) sui laterali (sinistri) di $H$, vale a dire $G\curvearrowright G/H=\lbrace xH\mid x\in G\rbrace$, $g(xH) \coloneqq gxH$.
  - Dimostrate che, per $x\in G$, lo stabilizzatore di $xH$ è $xHx^{-1}$.
  - Dimostrate che il numero di punti fissi dell'azione _ristretta ad_ $H$, i.e. il numero di laterali $xH$ tali che $gxH=xH$ per ogni $g\in H$, coincide con $[\mathbf{N}_G(H):H]$.
  - Supponiamo che $H$ sia un $p$-sottogruppo di $G$, cioè $|H|=p^k$ per qualche $k$ e un fissato primo $p$. Se $[G:H]$ è divisibile per $p$, mostrate che anche $[\mathbf{N}_G(H):H]$ è divisibile per $p$.
- (Dopo aver rivisto la teoria!) Usate l'esercizio precedente e il teorema di Cauchy (ma non i teoremi di Sylow!) per dimostrare che, se $G$ è un gruppo finito e $p$ è un primo che divide $|G|$, il gruppo $G$ ha un $p$-Sylow.  

**Tutorati 3-4:**
- dal libro, es. 122, 124, 128.
- Sia $G$ un gruppo finito tale che tutti i suoi sottogruppi massimali sono coniugati.
  - Provate che $G$ è un $p$-gruppo per qualche primo $p$.
  - Concludete che $G$ è ciclico di ordine $p^n$.
- Sia $G$ un gruppo di ordine $p^3q$, per certi primi $p,q$. Supponiamo che $n_p(G), n_q(G)>1$.  
  - Mostrate che dev'essere $|G|=24$.
  - ($\star$) Concludete che $G\simeq S_4$.
- Sia $G$ un gruppo, e sia $\varphi:G\to \text{Aut}(G)$ la mappa che manda $g\in G$ nel coniugio per $g$. Mostrate che $G\rtimes_\varphi G\simeq G\times G$.
- Sia $G$ un gruppo finito. 
  - Sia $G\curvearrowright X$ un'azione _transitiva_, e supponiamo che la sua restrizione a un sottogruppo $H < G$ sia ancora transitiva. Mostrate che allora $G=H\cdot\text{stab}_G(x)$ per un qualsiasi $x\in X$.
  - (Argomento di Frattini) Se $N < G$ è un sottogruppo normale di $G$, e $P$ è un $p$-Sylow di $N$, mostrate che $G=\mathbf{N}_G(P)\cdot N$.
- Sia $G$ un gruppo finito. Mostrate che le seguenti condizioni sono equivalenti. _Hint: l'ordine in cui mostrare le implicazioni è quello indicato. Per l'implicazione da 2. a 3. è utile l'esercizio precedente_.
  1) i normalizzatori dei sottogruppi di $G$ crescono, cioè: se $H\lneq G$, vale $\mathbf{N}_G(H)\supsetneq H$;
  2) i sottogruppi massimali di $G$ sono normali; 
  3) i $p$-Sylow di $G$ sono normali; 
  4) $G$ è prodotto diretto dei suoi $p$-Sylow;
  5) ogni quoziente non banale di $G$ ha centro non banale.
- (Una generalizzazione dell'esempio $S_3\rtimes \mathbb{Z}/2$) Sia $G=N\rtimes_\varphi H$ un prodotto semidiretto, e supponiamo che $Z(N)=1$ e $H$ agisca su $N$ per automorfismi _interni_, i.e. $\text{im}(\varphi)\subset\text{Inn}(N)<\text{Aut}(N)$. Mostrate che $G\simeq N\times \mathbf{C}_G(N)$.     
- Sia $G$ un gruppo di ordine $n$, e sia $\varphi:G\to S_n$ l'immersione di Cayley, i.e. quella indotta dall'azione $G\curvearrowright G$ per moltiplicazione.
  - ($\star$) Dimostrate che $\mathbf{N}_{S_n}(\varphi(G))\simeq G\rtimes \text{Aut}(G)$, con l'azione naturale di $\text{Aut}(G)$ su $G$.
  - Ritrovate (o deducete) il fatto seguente: se $\sigma\in S_n$ è un $n$-ciclo, $\mathbf{N}_{S_n}(\langle\sigma\rangle)\simeq \mathbb{Z}/n\rtimes(\mathbb{Z}/n)^*$.
 
**Tutorati 5-6:**

- Dal libro, es. 155, 164, 168, 181.
- Sia $A=\mathbb{Q}[x,y]$, e siano $\mathfrak{p}=(x^2+y)$, $\mathfrak{q}=(x^4+y)$. Mostrate che
  - $\mathfrak{p}$ e $\mathfrak{q}$ sono ideali primi di $A$,
  - $\mathfrak{p}+\mathfrak{q}$ è un ideale proprio di $A$ che non è primo.
- Sia $n>0$ un numero naturale. Dite per quali valori di $n$ l'anello $\mathbb{Z}/n$ è *ridotto*, cioè non ha elementi nilpotenti. 
- Supponiamo che un anello $A$ abbia infiniti ideali massimali. Mostrate che, se $\mathfrak{m}_1,\dots,\mathfrak{m}_k$ sono ideali massimali di $A$, con $k\in\mathbb{N}$, vale $\mathfrak{m}_1\cap\cdots\cap\mathfrak{m}_k\neq (0)$.
- Siano $A$ un anello e $x$ un'indeterminata.
  - Caratterizzate gli elementi nilpotenti di $A[ x ]$.
  - Caratterizzate gli elementi invertibili di $A[ x ]$.
- Esibite un anello commutativo $A$ (necessariamente senza $1$!) privo di ideali massimali.

**Tutorato 8:**

- dal libro, es. 157, 171, 176, 197;
- Sia $A$ un dominio. Mostrate che sono equivalenti le seguenti condizioni. *Leggero Hint per 3. implica 1.: localizzate.* 
  1) A è un UFD;
  2) ogni primo $\mathfrak{p}\subset A$ diverso da $(0)$ può essere generato da elementi primi;
  3) ogni primo $\mathfrak{p}\subset A$ diverso da $(0)$ contiene un elemento primo.
- Sia $A$ un dominio, e sia $S$ una sua parte moltiplicativa. Se $K=\text{frac}(A)$, mostrate che $S^{-1}A=A[S^{-1}]$, il più piccolo sottoanello di $K$ che contiene $A$ e gli inversi degli elementi di $S$.
- Sia $A$ un dominio. Se $S\subset A$ è una parte moltiplicativa, definiamo la *saturazione* di $S$ in $A$ come l'insieme $\text{sat}(S)$ degli $a\in A$ tali che $a$ divide $s$ per qualche $s\in S$. Mostrate che $\text{sat}(S)$ è ancora una parte moltiplicativa di $A$, e che $\text{sat}(\text{sat}(S))=\text{sat}(S)$.
- Sia $A$ un dominio. Mostrate che sono equivalenti, per $S,T\subset A$ parti moltiplicative:
  1) $S^{-1}A\simeq T^{-1}A$;
  2) $S^{-1}A=T^{-1}A$ in $\text{frac}(A)$;
  3) $\text{sat}(S)=\text{sat}(T)$.
- Trovate tutte le localizzazioni di $\mathbb{Z}$ a meno di isomorfismo, e di ognuna di esse caratterizzate gli ideali primi.
- Sia $A$ un PID. Se $\mathfrak{p}\subset A$ è un primo, contate gli ideali primi di $A_\mathfrak{p}$.
- Sia $A$ un dominio euclideo.
  1) Mostrate che è sempre possibile trovare un grado $d:A\setminus\lbrace 0\rbrace\to\mathbb{N}$ su $A$ tale che $\text{min}\lbrace d(a)\mid a\in A\rbrace=0$.
  2) Se $d$ è come in 1., mostrate che dev'essere $d(u)=0$ per ogni $u\in A^\times$. 
  3) Se $S\subset A$ è una parte moltiplicativa, dimostrate che $S^{-1}A$ è un dominio euclideo.  
- Sia $A$ un anello.
  1) Mostrate che, se $I\subset A$ è un ideale, vale $I\subset (I:a)(I,a)$ per ogni $a\in A$; esibite un caso in cui non vale l'uguaglianza.
  2) Mostrate che, se $A$ è un dominio i cui ideali *primi* sono principali, allora $A$ è un PID.

## Simulazioni d'Esame

- Simulazione 24 aprile (Gruppi): [Testo](/Compitino1.pdf), [Soluzioni](/CompitinoSoluzioni.pdf).


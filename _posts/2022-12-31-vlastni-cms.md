---
layout: post
title: "Až budu velká agoška, tak si naprogramuju vlastní CMSko"
permalink: /vlastni-cms/
date: 2022-12-31
author: Zdeněk Nešpor
tags: [weby]
---

Propadli jste touze po tvorbě vlastního CMS? Nebo si jako majitelé webů myslíte, že potřebujete nějaké custom řešení? Zkuste si přečíst tento článek a znovu se nad tím celým raději ještě jednou zamyslet.


Při psaní textu jsem si vzpomněl na níže uvedený rozhovor ze seriálu Červený trpaslík.

~~~
LISTER: Měl fůru podivnejch zvyků. Ale až teď mi došlo, jaký fakt byly...
KOCOUR: Debilní.
~~~
*Červený trpaslík, Série VII, Epizoda 5*

![Starbug v2](../assets/posts/2020-05-20-pixel-art-ii/starbug-2.png "Starbug v2"){: .align-left} Lister a Kocour vzpomínají na Rimmera. Ale klidně by to sedělo i na situaci, kdyby se bavili o podivném zvyku nejen českých agentur si programovat vlastní CMSka.

## Krutý úděl prokletých

Proklatce a nešťastníky je možné rozřadit do dvou skupin. Ty co vlastní CMS vyvíjí a ty co si ho v dobré víře koupí nebo pronajmou.

### Agentura

Možná ještě netušíte jaký bič jste si na sebe upletli. Nevadí. Brzy poznáte.

Teď možná máte skvělou vizi, připravenou roadmapu a jste celí žhaví udělat revoluci ve světě CMS. Ve chvíli, kdy získáte první dva klienty, kteří budou potřebovat custom úpravy se všechno rozpadne jako domeček z karet.  

Na opravdu světoznámých frameworcích a CMSkách dělají stovky lidí mnoho let. Proč si proboha myslíte, že v týmu 5 lidí z toho třemi junior developery, a velkou fluktuací zaměstnanců dokážete udělat lepší systém, než ty které už existují?

### Klient

Platíte agentuře za to, že vám dodává řešení na míru? Upřímnou soustrast. Dostali jste se do jedné z největších pastí. Stručně vysvětlím jak to zpravidla funguje.

Custom řešení nemá se skutečným custom řešením vůbec nic společného. Agentura má nějaké svoje CMS, které si sami interně naprasili dohromady. Tohle pseudo-generické řešení bude základ vašeho webu. Z jádra CMSka vyroste větev, na které vám vyrobí nějaké úpravy "na míru". To obvykle znamená, že maximálně dostanete svoji vlastní šablonu.

Udělat skutečnou custom úpravu není vůbec jednoduché. Na WordPress si jednoduše koupíte plugin za tisícovku. Za triviální custom úpravu dáte kolem 20 000 Kč a ještě to třikrát vrátíte na přepracování. Ten kdo programoval custom CMS ve firmě už dávno není. Jádro nikdo ze současných zaměstnanců nezná a budou se v tom plácat desítky hodin.

### Proč to existuje?

Custom řešení webů jsou jednoduše základní agenturní pasti, jak mít dlouhodobě stabilní klientelu. Z custom řešení se totiž blbě přechází.

Obvykle se přechází z generických řešení na custom řešení.

A z custom řešení se přechází na jiná custom řešení. Ne protože by to někdo reálně chtěl, ale protože to bývá jediná cesta, jak web zachránit. Klíčových problém je nejčastěji databáze. Agentura A má nějaký systém. Ten není kompatibilní s čímkoliv. A nikdo se nebude dvakrát snažit vám ten přechod usnadnit. Proto půjdete za agenturou B, která vám slíbí, že vaše nové řešení bude pochopitelně custom made a tu databázi vám přenesou. Ale bude to stát o něco víc, protože to je custom úprava navíc. A jste uvěznění ve světě předražených custom nesmyslů.

### Vendor lock-in

Říká se tomu vendor lock.

https://en.wikipedia.org/wiki/Vendor_lock-in

### In-house

Nejlepší cesta na custom made řešení je mít in-house vývoj. Dovolit si to ovšem mohou jen ti největší hráči. To že máte interně dva vývojáře, kteří dělají nějaké feedy, integrace a starají se o databázi, neznamená, že máte dost lidí na vývoj vlastního řešení nebo drastické modifikace nějakého krabicového řešení.

### Hororový příběh dle skutečných událostí

Zákazník se rozhodl odejít od jedné nejmenované agentury z Ostravy. Ve chvíli, kdy se rozhodl ke změně CMS a dal výpověď ze smlouvy byl do druhého dne kompletně ukončen provoz jeho webu, který několik let budoval. Jediné co mu zbylo byla doména, kterou měl ve svém vlastnictví. Co se stalo?

* E-shopové řešení měl od agentury jen v pronájmu. Dle smlouvy vše patřilo agentuře, která klienty, kteří se rozhodli odejít "trestala" kompletním vypnutím webu a zabavením veškerých dat. To se týkalo kompletně dat o objednávkách, zákaznících, ale i Google Analytics, které agentura také vlastnila.

Asi po měsíci dohadování agentura souhlasila, že klientovi alespoň exportuje databázi objednávek a e-mailů jeho zákazníků. Za 20 000 Kč, protože se prý jedná o nestandardní a časově náročný úkon. A to prý ještě může být rád, že jsou vůbec ochotní se tomu věnovat.

Stalo se to někdy kolem let 2016-2017. Klientovi tehdy zůstala jen doména a 10 let starý seznam mrtvých zákaznických e-mailů, které měl zálohované ještě z předchozího řešení. Pro již zkomírající byznys to byla bohužel poslední rána.

Čtěte smlouvy. Hledejte si reference. Nespolupracujte se šmejdy.

## Agenturní CMS


## Proč se v agentuře nenaučíte dělat něco opravdu užitečného a smysluplného?

Chcete být užiteční? Existují desítky docela fajn řešení. Jedno si vyberte a naučte se s ním dělat. Ale pořádně, do hloubky. Ne že systém nainstalujete a proklikáte si administraci. Místo roku vývoje vlastního CMS investujte rok do důkladného prozkoumání a výběru kvalistního CMS, které budete používat.

## Dostupná řešení



### Na takové to obyčejné blogování

**Jekyll** je minimalistické řešení, na kterém běží například tento blog. Jedná se o extrémně jednoduché bezdatabázové CMS, které zvládá fungovat i na Githubu. Má svoje omezení.

**Ghost** je krásné, minimalistické a extrémně rychlé řešení. Má dvě nevýhody. Vlastní instalace vyžaduje server s podporou NodeJS, což v ČR nabízí snad pouze hosting exon.io. A placená cloudová verze není zrovna levná.

### Chci větší web

**Wordpress**. Můžete ho nenávidět. Můžete ho milovat. Ale to je asi tak všechno. Existuje řadu let a ještě dlouho bude. Je zadarmo, má hromadu šablon a pluginů. Jde na něm postavit skoro všechno. A má obrovskou komunitu uživatelů.

### Na funkční e-shop

**Shoptet**. Nic jiného nepotřebujete a hodně dlouho potřebovat nebudete. *Ale dyť je to placený, ty jo.* Ano, ale cena je velice férová. Shoptet je zavedené řešení. GDPR ready, hromada funkčních integrací, adekvátní design, slušná podpora, velká komunita uživatelů. Tohle přesně chcete.

Klidně si vyberte něco jiného. Řešení jsou vyšší desítky. Mnoho z nich je dostupných i zdarma. Například WordPress s WooCommerce nebo Prestashop. Poměrně rychle zjistíte, že údržba takovýchto řešení je oser a že to není vůbec sranda.

### Čemu a komu se raději vyhnout

Moc rád bych tu sepsal seznam řešení a firem, kterým byste se měli vyhnout. Bohužel to dost dobře nejde, aby

* Wix
* Solidpixels
* Drupal
* Joomla
* Medium
* Eshop-rychle.cz
* Liferay

## Závěrem

test

### Dodatek

Možná je to všechno tím, že dobré weby se SEO specialistům do rukou moc nedostávají.

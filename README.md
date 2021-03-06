# OpenCore 0.6+ patch dei componenti

## Descrizione
La serie di patch si basa sui requisiti e sui suggerimenti di OpenCore 0.6+.


## Il GitBook
Questo repository si basa su GitBook e utilizza le azioni Github per creare il servizio Page e il manuale PDF.

- [https://ocbook.tlhub.cn](https://ocbook.tlhub.cn)
- [OpenCore component patches](https://cdn.jsdelivr.net/gh/daliansky/OC-little/docs/OpenCore部件库.pdf)

## Sommario

0. **Panoramica**

   1. Basic ACPI Source Language
   2. Sequenza di caricamento SSDT
   3. Modulo ACPI
   4. Tabella comparativa ASL-AML

1. **Informazioni su `AOAC**

   1. Impedire lo sleep `S3`
   2. `AOAC` disabilitare la scheda grafica discreta
   3. Risparmio energetico profondo
   4. Patch di riattivazione `AOAC`
   5. Impostare lo stato `ASPM`
   6. Disattivazione automatica di `WIFI` durante il sonno

2. **Variabile preimpostata**

   1. Patch OC `I2C-GPIO`
   2. Patch correlate

3. **Dispositivi falsi**

   1. Falsi `EC`
   2. RTC0
   3. Falso sensore di luce ambientale (ALS)

4. **Patch del sistema operativo**

5. **Dispositivi di iniezione**

   1. Iniettare X86
   2. Metodo di iniezione `PNLF`
   3. Patch `SBUS (SMBU)`

6. **Aggiungi componenti mancanti**

7. **Mappatura tastiera PS2 e tasto funzione luminosità @ OC-xlivans**

8. **Patch batteria**

   1. Thinkpad
   2. Altre marche
   3. Patch indicatore di stato della batteria
   4. Esempi

9. **Disattivazione EHCx**

10. **Patch delle estensioni `PTSWAK`**

11. **Metodo di regolazione dello sleep `PNP0C0E`**

12. **Patch `0D6D`**

    1. Patch generale `060D`
    2. Patch HP `060D`

13. **Fake Ethernet e ripristino Ethernet `BSD Name`**

14. **Informazioni su `CMOS`**

    1. Memoria `CMOS` e ***RTCMemoryFixup***

15. **Porte `ACPI` Patch` USB`**

16. **Disattivazione dei dispositivi `PCI`**

17. **ACPIDebug**

18. **Patch per marche specifiche**

    1. Patch `Dell`
    2. Patch `XiaoXin PRO13`
    3. Patch `ThinkPad`

19. **Dispositivo `I2C`**

20. **Disattivazione della scheda grafica discreta tramite `SSDT`**

**Patch riservate**

   1. Patch `IRQ` della scheda audio
   2. Patch di ripristino `CMOS`

**Elenchi di carico delle unità comuni**

   1. liste di caricamento config-1-Lilu-SMC-WEG-ALC
   2. liste di caricamento delle unità della tastiera config-2-PS2
   3. liste di caricamento unità wireless e bluetooth config-3-BCM
   4. liste di caricamento di config-4-I2C + PS2
   5. Liste di caricamento dei drvices della tastiera config-5-PS2Smart
   6. liste di caricamento delle unità wireless e bluetooth config-6-Intel
   
##
### Credits 

- Credits to：
  - [Daliansky](https://github.com/daliansky) per le informazioni e la repo **[daliansky](https://github.com/daliansky/OC-little)** 
  - [Williambj1](https://github.com/williambj1)
  - [Team Acidanthera](https://github.com/acidanthera) per [OpenCorePkg](https://github.com/acidanthera/OpenCorePkg)**


# Se hai bisogno di supporto qui [Telegram](https://t.me/HackintoshLife_it) o [Web](https://www.hackintoshlife.it/)

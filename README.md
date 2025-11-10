=== Piero Import ===
Contributors: piero
Tags: woocommerce, import, csv, xml, batch, cron, wp-cli
Requires at least: 5.0
Tested up to: 6.5
Requires PHP: 7.2
Stable tag: 1.0.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Plugin avanzato per importare e aggiornare prodotti WooCommerce da file CSV o XML, con supporto per cron job, WP-CLI e mappature personalizzate.

== Description ==

Piero Import è un plugin per WooCommerce che permette di importare e aggiornare prodotti da file CSV o XML. Supporta funzionalità avanzate come:

- Gestione fornitori con impostazioni dedicate
- Mappatura campi completa
- Importazioni manuali o pianificate
- Compatibilità WP-CLI
- Gestione immagini (galleria, sostituzioni)
- Report dettagliati
- Elaborazione batch per file grandi
- Supporto per categorie multilivello, prodotti variabili, SEO e altro

== Installation ==

1. Carica il plugin nella directory `/wp-content/plugins/`.
2. Attiva il plugin dal menu "Plugin" di WordPress.
3. Vai su "Piero Import" nel menu di amministrazione per iniziare.

== Usage ==

1. Aggiungi un fornitore con URL del file e tipo (CSV o XML).
2. Mappa i campi del file ai campi WooCommerce tramite Template.
3. Imposta le categorie e le opzioni di aggiornamento.
4. Avvia l’importazione manualmente o pianifica con WP Cron o cron job.
5. Monitora l’import con barra di progresso e scarica il report finale.

== WP-CLI ==

Puoi eseguire importazioni da terminale con:

`wp piero-import run 123 1-100 --sleep=2`

== Frequently Asked Questions ==

= È compatibile con file grandi? =
Sì, puoi regolare la dimensione dei batch per ottimizzare memoria e prestazioni.

= Posso usare un cron job reale? =
Sì, viene fornito un URL sicuro con chiave da usare nel cron server.

= Supporta prodotti variabili? =
Sì, con attributi personalizzati e mappatura delle variazioni.

== Changelog ==

= 1.0.0 =
* Versione iniziale del plugin.

== Upgrade Notice ==

= 1.0.0 =
Prima versione stabile.

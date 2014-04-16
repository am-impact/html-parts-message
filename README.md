# html-parts-message

Uitbreiding op [html startup](https://github.com/am-impact/html-startup)

## Bestanden
 * content/sass/components/_message.scss

## Voorbeelden

### Html
 	<div class="message">Standaard melding</div>
    <div class="message message--succes">Succes bericht</div>
    <div class="message message--notice">Notice bericht</div>
    <div class="message message--error">Fout bericht</div>

### Scss
###### _settings.scss
 	$colors: (
    	message: (
	        default: #2ba6cb,
	        succes: #5da423,
	        error: #c60f13,
	        notice: #e7d432
    	)
    )


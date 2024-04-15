# EPGItaly-Homeassistant
Goal: EPG TV Italy on HomeAssistant

  * note: 
	* this flow depend on (https://tvit.leicaflorianrobert.dev/)
	   * https://tvit.leicaflorianrobert.dev/iptv/list.json
             now and next live data
      
## Requirement ##
* NodeRed on HomeAssistant
* NodeCompanion on HomeAssistant

* ## Install ##
* NodeRed:
	* Import flow json
	* Deploy

 ![immagine](https://github.com/sdavides/EPGItaly-Homeassistant/assets/31100253/919c9993-5682-4323-93db-8c180cacff95)


## Example panel: ##

![immagine](https://github.com/sdavides/EPGItaly-Homeassistant/assets/31100253/d3d2ab66-5160-4bd7-98f7-b7a9ec3d5475)







## TIPS ##

* Live streaming on Android ( mediaset and others available 13/04/2024 )
* Update data: ( add two automation )
  * example_automation_every_4min.yaml
  * example_automation_every_00_01.yaml
* Send notification next scheduler of my favorite show:
  * example_alert_simpson.yaml
  * example_alert_city_hunter.yaml
  * example_alert_f1_allchannels.yaml (search F1 on all channels on nexttitle)
  * example_alert_pozzetto_allchannels_descr.yaml (search Pozzetto on all channels on nextdescription)
    
* Create dashboard page ( example_panel.yaml, need card_mod )
  
## Example ##
![immagine](https://github.com/sdavides/EPGItaly-Homeassistant/assets/31100253/19636c5c-e9e5-4d8f-ae6e-ebe6afa80618)


 ## Alert ##
![immagine](https://github.com/sdavides/EPGItaly-Homeassistant/assets/31100253/de0948e4-530f-4be4-8d8f-73d0e8685217)

## Mobile ##
![immagine](https://github.com/sdavides/EPGItaly-Homeassistant/assets/31100253/8b7a2ae1-d8da-4a69-8e4d-5d1e6fbf11eb)



<script src='https://meet-e-huquqtartibot.unicon.uz/external_api.js'></script>

<div id="meet">
</div>

<script>

const domain = 'meet-e-huquqtartibot.unicon.uz';

const options = {
    roomName: 'mvd_test',
    width: 700,
    height: 700,
    parentNode: document.querySelector('#meet'),
    lang: 'en',
    userInfo: {
        displayName: 'Abdullo Xidoyatov'
    },

    interfaceConfigOverwrite: {
	SHOW_JITSI_WATERMARK: false
    },
 
    configOverwrite: {
    	prejoinConfig: {
      		enabled: false
    	},

	toolbarButtons: [
		'hangup','microphone','camera','toggle-camera','videoquality'
	],

	disable1On1Mode:false,

	p2p: {
		enabled: true
	},

        participantsPane: {
		enabled: false
    	}

    },

};
const api = new JitsiMeetExternalAPI(domain, options);

</script>






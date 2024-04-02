




<script src='https://meet.jit.si/external_api.js'></script>

<div id="meet">
</div>


<script>

const domain = 'meet.jit.si';
const options = {
    roomName: 'mvd_test',
    width: 700,
    height: 700,
    parentNode: document.querySelector('#meet'),
    lang: 'en',
    userInfo: {
        displayName: 'Fazullo Xidoyatov'
    },

    interfaceConfigOverwrite: {
	SHOW_JITSI_WATERMARK: false
    },
 
    configOverwrite: {
    	prejoinConfig: {
      		enabled: false
    	},

	toolbarButtons: [
		'hangup'
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






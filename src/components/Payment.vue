<template>
  <div>
    <div id="w-node-_102b9f5c-9c6d-f0f4-9254-ad66bae0c3cf-3b5a16c8" class="page-link">
      <div class="div-block-39">
        <div class="text-block-7">STAP 2 VAN 3</div>
        <div class="text-block-8">Betaling</div>
        <p>Door het verzenden van dit formulier wordt uw aanmelding naar de respectievelijke stad gestuurd.</p>
        <div>
          <div class="text-block-9 mb-10">Type betaling:</div>
          <div class="div-block-46">
            <div class="div-block-47">
              <div id="w-node-fcc6336e-a653-adce-4d54-82374cb47de6-3b5a16c8" class="div-block-48"><img
                  src="images/New-Project.png" loading="lazy" alt="" class="image-9"></div>
              <div id="w-node-_44044055-1812-a98b-b6e0-15ebd98230df-3b5a16c8" class="div-block-48"><img
                  src="images/donatieschermen-1-1.png" loading="lazy" alt="" class="image-9 _2"></div>
              <div id="w-node-_9713f0ab-f885-4bfc-c7ca-77f65a95ab88-3b5a16c8" class="div-block-48"><img
                  src="images/donatieschermen-1-3.png" loading="lazy" alt="" class="image-9 _2"></div>
              <div id="w-node-eee9be58-dcf3-8567-95df-ff8af9d7a807-3b5a16c8" class="div-block-48"><img
                  src="images/donatieschermen-1-2.png" loading="lazy" alt="" class="image-9"></div>
            </div>
          </div>
        </div>
        <div class="div-block-45"><label class="w-checkbox checkbox-field"><input type="checkbox" id="checkbox-11"
              name="checkbox-11" data-name="Checkbox 11" class="w-checkbox-input"><span class="w-form-label"
              for="checkbox-11">Ik geef toestemming om deze persoonsgegevens te verwerken.</span></label></div>
      </div>
      <div class="div-block-40">
        <div class="div-block-41">
          <div>Kies je stad :</div>
          <div data-hover="false" data-delay="0" class="w-dropdown">
            <div class="dropdown-toggle-3 w-dropdown-toggle">
              <div class="icon-4 w-icon-dropdown-toggle"></div>
              <div class="text-block-10">Landelijk bestuur</div>
            </div>
            <nav class="w-dropdown-list">
              <a href="#" class="w-dropdown-link">Link 1</a>
              <a href="#" class="w-dropdown-link">Link 2</a>
              <a href="#" class="w-dropdown-link">Link 3</a>
            </nav>
          </div>
        </div>
        <a href="#" class="button-4 w-button">Doneer nu</a>
      </div>
    </div>
  </div>
</template>


<script>

    
    export default {
        components: {

},
        props: [
            "input_var",
        ],
        data: () => {
            return {
                // example1: "hoi"
            }
        },
        methods: {
            // clickMethod( input_var ) {
    
            // return output
            // }
        },   
    
    }
var url = null

    await axios(config)
    .then(function(response){
      return res.json(response.data);

    });

    window.open(url)
</script>
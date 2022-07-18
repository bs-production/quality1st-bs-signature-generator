<template>
  <div>
      <section>
        <table cellpadding="0" cellspacing="0" border="0" style=
        "background: none; border-width: 0px; border: 0px; margin: 0; padding: 0;">
        <tr>
            <td valign="top" style="padding-top: 0; padding-bottom: 0; padding-left: 0; padding-right: 7px; border-top: 0; border-bottom: 0: border-left: 0;">
              <a href="https://www.connecticutbasementsystems.com">
                <img v-show="mobilePhoneSwitch" width="220" height="139" style="width: 220px; max-width: 220px !important; height: 139px; max-height: 139px !important; margin-top: 5px;" id="preview-image-url" src="https://dc69b531ebf7a086ce97-290115cc0d6de62a29c33db202ae565c.ssl.cf1.rackcdn.com/7/signature-logo-bar.png" name="preview-image-url" />
        
                <img v-show="!mobilePhoneSwitch" width="190" height="121" style="width: 190px; max-width: 190px !important; height: 121px; max-height: 121px !important; margin-top: 5px;" id="preview-image-url" src="https://dc69b531ebf7a086ce97-290115cc0d6de62a29c33db202ae565c.ssl.cf1.rackcdn.com/7/signature-logo-bar.png" name="preview-image-url" />
              </a>
            </td>
            
            <td style=
            "padding-top: 0; padding-bottom: 0; padding-left: 5px; padding-right: 0;">
            <table cellpadding="0" cellspacing="0" border="0" style=
            "background: none; border-width: 0px; border: 0px; margin: 0; padding: 0;">
              <tr>
                  <td colspan="2" style=
                  "padding-bottom: 5px; color: #1aaee4; font-size: 18px; font-family: Arial, Helvetica, sans-serif;">
                  {{fullName}}
                  </td>
                </tr>
                <tr>
                  <td colspan="2" style=
                  "color: #333333; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                  <em>{{title}}</em>
                  </td>
                </tr>
              <div v-show="!mobilePhoneSwitch">

              </div>
             
                <tr>
                  <td width="20" valign="top" style=
                  "vertical-align: top; width: 20px; color: #1aaee4; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                  Phone:
                  </td>
                  <td valign="top" style=
                  "vertical-align: top; color: #333333; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                  {{phone}}
                  </td>
                </tr>
                <tr v-show="mobilePhoneSwitch">
                <td width="20" valign="top" style=
                  "vertical-align: top; width: 20px; color: #1aaee4; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                  Mobile:
                  </td>
                  <td valign="top" style=
                  "vertical-align: top; color: #333333; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                  {{mobilePhone}}
                  </td>
                </tr>
                <tr>
                    <td width="20" valign="top" style=
                    "vertical-align: top; width: 20px; color: #1aaee4; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                    Email:
                    </td>
                    <td valign="top" style=
                    "vertical-align: top; color: #333333; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                    <a :href="`mailto:${this.email}`" style="color: #333333; text-decoration: none; font-weight: normal; font-size: 14px;">{{email}}</a>
                      &nbsp;&nbsp;
                    </td>
                  </tr>
                <tr>
                  <td width="20" valign="top" style=
                  "vertical-align: top; width: 20px; color: #1aaee4; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                  Web:
                  </td>
                  <td valign="top" style=
                  "vertical-align: top; color: #333333; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                  <a href="https://www.connecticutbasementsystems.com" style=
                  "color: #333333; text-decoration: none; font-weight: normal; font-size: 14px;">
                    connecticutbasementsystems.com</a>
                    &nbsp;&nbsp;
                  </td>
                </tr>
                <tr>
                  <td colspan="2" style="padding-top: 5px;">
                    <a href="https://www.facebook.com/connecticutbasementsystems/" style=
                    "border-width:0px; border:0px; text-decoration: none;"><img width="25"
                    height="25" style=
                    "border: none; width: 25px; max-width: 25px !important; height: 25px; max-height: 25px !important;"
                    src=
                    "https://dc69b531ebf7a086ce97-290115cc0d6de62a29c33db202ae565c.ssl.cf1.rackcdn.com/1874/facebook.png" /></a>
                    <a href="https://www.instagram.com/ctbasementsystems/"
                    style=
                    "border-width:0px; border:0px; text-decoration: none;"><img width="25"
                    height="25" style=
                    "border: none; width: 25px; max-width: 25px !important; height: 25px; max-height: 25px !important;"
                    src=
                    "https://dc69b531ebf7a086ce97-290115cc0d6de62a29c33db202ae565c.ssl.cf1.rackcdn.com/1874/instagram.png" /></a>
                    <!-- <a href="https://www.linkedin.com/company/basement-systems-of-indiana" style=
                    "border-width:0px; border:0px; text-decoration: none;"><img width="25"
                    height="25" style=
                    "border: none; width: 25px; max-width: 25px !important; height: 25px; max-height: 25px !important;"
                    src=
                    "https://dc69b531ebf7a086ce97-290115cc0d6de62a29c33db202ae565c.ssl.cf1.rackcdn.com/1874/linkedin.png" /></a> -->
                    
                    <a href="https://twitter.com/CTBasementSys" target="_blank"
                    style=
                    "border-width:0px; border:0px; text-decoration: none;"><img width="25"
                    height="25" style=
                    "border: none; width: 25px; max-width: 25px !important; height: 25px; max-height: 25px !important;"
                    src=
                    "https://dc69b531ebf7a086ce97-290115cc0d6de62a29c33db202ae565c.ssl.cf1.rackcdn.com/1253/twitter-circle-icon-2.png" /></a>
                    <a href="https://www.youtube.com/user/CTBasementSystems"
                    style=
                    "border-width:0px; border:0px; text-decoration: none;"><img width="25"
                    height="25" style=
                    "border: none; width: 25px; max-width: 25px !important; height: 25px; max-height: 25px !important;"
                    src=
                    "https://dc69b531ebf7a086ce97-290115cc0d6de62a29c33db202ae565c.ssl.cf1.rackcdn.com/1874/youtube.png" /></a>
                            <a href="https://www.connecticutbasementsystems.com/quick-survey"
                    style=
                    "border-width:0px; border:0px; text-decoration: none;"><img width="152"
                    height="25" style=
                    "border: none; width: 152px; max-width: 152px !important; height: 25px; max-height: 25px !important;"
                    src="https://cdn.treehouseinternetgroup.com/cms_images/7/google-logo-text.png" /></a>
                  </td>
                </tr>
              </table>
            </td>
          </tr>
        </table>
    </section>
            <p style="text-align: left;"><strong>Discover all of our services: </strong><a href="http://www.ctbasementcompanies.com/">ctbasementcompanies.com</a></p>
  </div> 
</template>
<script>
export default {
  name: 'outputSignature',
  props: {
    fullName: {
      type: String,
      required: true
    },
    title: {
      type: String,
      required: true
    },
    mobilePhone: {
      type: String,
      required: true
    },
    phone: {
      type: String,
      required: true
    },
    email: {
      type: String,
      required: true
    },
    mobilePhoneSwitch: {
      type: Boolean,
      required: true
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #1aaee4;
}
</style>

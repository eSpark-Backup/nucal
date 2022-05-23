<template>
  <NucGridPage v-bind:gap="{'col':0,'row':0}" v-bind:rows="[1]"
    v-bind:schema="{'r0-c0':{'col':0,'row':0,'showIn':['xs','sm','md','lg'],'colSpan':1,'rowSpan':1}}"
    v-bind:columns="[1]" overflow="auto" v-bind:designMode="false" v-bind:minNsLimit="158"
    v-bind:style="{'background':'#e6e6e6','paddingTop':'0px','paddingLeft':'0px','paddingRight':'0px','paddingBottom':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="203fc515-16d5-4dcb-8b19-f8b0ac8acb7a" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <WBoxColorAdvertisement top="25.06265664160401%" left="40.21978021978022%" name="b-card" v-bind:blank="true"
        v-bind:snapX="false" v-bind:snapY="false" imgSrc="" v-bind:overlay="true" cardText="" position="absolute"
        bgVariant="primary" changeColor="#FFFFFF" textVariant="white"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'imgSrc','displayName':'ImageUrl'},{'type':'string','propName':'cardText','displayName':'Value'}]}"
        nucalScaleWidth="0.301NS" nucalScaleHeight="0.373NS" verticalPosition="align-items-center"
        horizontalPosition="justify-content-center" id="b0f0bac1-8652-423e-97c0-75c403513d4b"
        v-bind:style="{'maxWidth':'','minWidth':'','marginTop':'0px','maxHeight':'','minHeight':'','marginLeft':'0px','paddingTop':'0px','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px'}">
        <NucInput top="16.83461502825906%" left="23.208062369271726%" text="" theme="theme--light01" maximum="100"
          minimum="0" position="absolute" tabIndex="0" isEnabled="Enable" v-bind:isMasking="false" ncInputType="text"
          placeholder="" v-bind:previewMode="true" ncTypography="body1" ncTooltipText=""
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':true,'structure':[{'type':'string','ncKey':'type','ncType':{'ncInputType':'number'},'ncValue':'number','propName':'text','displayName':'Value','nsDefaultValue':'string'}]}"
          nucalScaleWidth="" ncClickFontColor="#434855" ncFocusFontColor="#434855" ncHoverFontColor="#434855"
          nucalScaleHeight="" ncClickBorderColor="#000000" ncDisableFontColor="#434855" ncFocusBorderColor="#000000"
          ncHoverBorderColor="#000000" ncDisableBorderColor="#000000" ncClickBackgroundColor="#ffffff"
          ncFocusBackgroundColor="#ffffff" ncHoverBackgroundColor="#ffffff" ncDisableBackgroundColor="#ffffff"
          id="bb317355-97fb-41d0-ba54-14562e268a33"
          v-bind:style="{'color':'#000000','fontSize':'12px','maxWidth':'','minWidth':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','background':'#FFFFFF','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1','marginLeft':'0px','paddingTop':'0px','visibility':'visible','borderColor':'#D1D1D6','borderStyle':'solid','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','borderBottomWidth':'1px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px'}"/>
        <WEmailInput id="d53f9413-6607-4e69-8973-4a3a392fe52c" top="18.014639117946817%" v-bind:lazy="false"
          left="34.68644228940863%" size="md" text="" v-bind:trim="false" v-bind:noWheel="false" v-bind:disabled="false"
          position="absolute" v-bind:readonly="false" v-bind:required="false" wordList="" v-bind:autofocus="false"
          v-bind:plaintext="false" background="" ariaInvalid="false" v-bind:debounceVal="0" ncInputType="email"
          placeholder="" v-bind:previewMode="true" autocomplete="" ncTypography="body1" v-bind:lazyFormatter="false"
          ncTooltipText="" v-bind:isWordListOpen="false"
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':true,'structure':[{'type':'string','ncKey':'type','ncType':{'ncInputType':'number'},'ncValue':'number','propName':'text','displayName':'Value','nsDefaultValue':'string'}]}"
          v-bind:isNumberConvert="false" nucalScaleWidth="" ncClickFontColor="#434855" ncFocusFontColor="#434855"
          ncHoverFontColor="#434855" ncMaxNumberValue="100" ncMinNumberValue="0" nucalScaleHeight=""
          ncClickBorderColor="#000000" ncDisableFontColor="#434855" ncFocusBorderColor="#000000"
          ncHoverBorderColor="#000000" ncDisableBorderColor="#000000" formatterFunctionName=""
          ncClickBackgroundColor="#ffffff" ncFocusBackgroundColor="#ffffff" ncHoverBackgroundColor="#ffffff"
          ncDisableBackgroundColor="#ffffff"
          v-bind:style="{'color':'','fontSize':'12px','maxWidth':'','minWidth':'158px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1','marginLeft':'0px','paddingTop':'0px','visibility':'visible','borderColor':'#D1D1D6','borderStyle':'solid','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none'}"/>
        <WLightDropdown top="39.17007937243275%" v-bind:lazy="false" left="22.008138429359192%" role="menu" size="md"
          text="Light" type="simple" v-bind:block="false" v-bind:right="false" theme="theme--light01"
          v-bind:noFlip="false" offset="0" v-bind:noCaret="false" v-bind:options="[]" splitTo="" variant="light"
          position="absolute" v-bind:selected="[]" dataModel="" v-bind:isEnabled="true" splitHref=""
          visibility="visible" dataLoading="" v-bind:splitButton="false" ncTypography="body1" splitVariant="secondary"
          buttonContent="" dataModelType="" ncTooltipText="" variantOfItem=""
          v-bind:nucalDataModel="{'type':'NSW','isList':true,'update':{'dataModel':'dataModel'},'dynamic':true,'dataModel':'','structure':[{'type':'','update':{'type':'dataModelType','dataModel':'dataModel'},'propName':'options','dataModel':'','displayName':'Value'}]}"
          dropdownOptions="" nucalScaleWidth="" splitButtonType="button" nucalScaleHeight=""
          v-bind:isButtonContentOpen="false" id="80a0cd5b-2534-4539-aaa9-aaa65cdb0bcc"
          v-bind:style="{'color':'#000000','width':'','fontSize':'16px','maxWidth':'','minWidth':'','fontStyle':'normal','marginTop':'','maxHeight':'','minHeight':'','textAlign':'center','background':'#ffffff','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','marginLeft':'','paddingTop':'','visibility':'visible','marginRight':'','paddingLeft':'','marginBottom':'','paddingRight':'','paddingBottom':'','textDecoration':'none'}"/>
        <WPrimaryDropdown top="62.887179962321255%" v-bind:lazy="false" left="52.40425936489827%" role="menu" size="md"
          text="Primary" type="simple" v-bind:block="false" v-bind:right="false" theme="theme--light01"
          v-bind:noFlip="false" offset="0" v-bind:noCaret="false" v-bind:options="[]" splitTo="" variant="primary"
          position="absolute" v-bind:selected="[]" dataModel="" v-bind:isEnabled="true" splitHref=""
          visibility="visible" dataLoading="" v-bind:splitButton="false" ncTypography="body1" splitVariant=""
          buttonContent="" dataModelType="" ncTooltipText="" variantOfItem=""
          v-bind:nucalDataModel="{'type':'NSW','isList':true,'update':{'dataModel':'dataModel'},'dynamic':true,'dataModel':'','structure':[{'type':'','update':{'type':'dataModelType','dataModel':'dataModel'},'propName':'options','dataModel':'','displayName':'Value'}]}"
          dropdownOptions="" nucalScaleWidth="" splitButtonType="button" nucalScaleHeight=""
          v-bind:isButtonContentOpen="false" id="0774a055-2b6d-40b5-8743-852ad8ab4f27"
          v-bind:style="{'color':'#FFFFFF','width':'','fontSize':'16px','maxWidth':'','minWidth':'','fontStyle':'normal','marginTop':'','maxHeight':'','minHeight':'','textAlign':'center','background':'#ffffff','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','marginLeft':'','paddingTop':'','visibility':'visible','marginRight':'','paddingLeft':'','marginBottom':'','paddingRight':'','paddingBottom':'','textDecoration':'none'}"/>
        <WDefaultCheckbox top="55.36823249637111%" left="20.749800342270394%" size="md"
          label="I accept the terms and use" v-bind:plain="false" theme="theme--light01" v-bind:value="true"
          v-bind:inline="false" fontSize="14px" position="absolute" v-bind:autofocus="false" v-bind:isEnabled="true"
          textAlign="left" fontFamily="Roboto-Regular,Roboto" fontWeight="normal" ncTypography="custom"
          v-bind:indeterminate="false" labelPosition="right" ncTooltipText="" v-bind:checkboxSwitch="false"
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'boolean','propName':'value','displayName':'Value'},{'type':'string','propName':'label','displayName':'Display'}]}"
          nucalScaleWidth="" ncFocusFontColor="black" ncHoverFontColor="black" nucalScaleHeight=""
          ncDisableFontColor="black" ncFocusBorderColor="black" ncHoverBorderColor="black" ncDisableBorderColor="black"
          ncFocusBackgroundColor="transparent" ncHoverBackgroundColor="transparent"
          ncDisableBackgroundColor="transparent" id="f6ed036f-6b87-4e76-99fb-58ed2c2c4545"
          v-bind:style="{'color':'','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'none','marginTop':'0px','maxHeight':'','minHeight':'','lineHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none'}"/>
        <WButton tag="button" top="60.30711263473239%" left="73.59056854915383%" v-bind:pill="false" size="md"
          text="Button" type="button" v-bind:block="false" color="" theme="theme--light01" v-bind:squared="false"
          variant="primary" position="absolute" v-bind:isEnabled="true" background="" borderColor=""
          ncTypography="body1" v-bind:resetTrigger="false" ncTooltipText="" verticalWidth="60px"
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
          textDecoration="none" verticalHeight="60px" horizontalWidth="72.4479px" nucalScaleWidth=""
          horizontalHeight="37.5347px" ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF"
          nucalScaleHeight="" ncClickBorderColor="#4285f4" ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#4285f4"
          ncHoverBorderColor="#4285f4" ncDisableBorderColor="transparent" ncClickBackgroundColor="#4285f4"
          ncFocusBackgroundColor="#4285f4" ncHoverBackgroundColor="#4285f4" ncDisableBackgroundColor="#969696"
          id="82a37f5d-5f4f-4a81-a989-4e3fe86f7f7b"
          v-bind:style="{'width':'','height':'','fontSize':'12px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'','maxHeight':'','minHeight':'','textAlign':'center','fontFamily':'OpenSans-Bold,Open Sans','fontWeight':'normal','lineHeight':'1.4','marginLeft':'','paddingTop':'','textShadow':'','visibility':'visible','borderStyle':'solid','marginRight':'','paddingLeft':'','marginBottom':'','paddingRight':'','paddingBottom':'','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','horizontalHeight':'37.5347px','borderBottomWidth':'1px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px'}"/>
        <WLink top="76.92294388338121%" href="" left="18.58912340749192%" v-bind:exact="false" v-bind:active="false"
          v-bind:append="false" caption="Link" v-bind:disabled="false" position="absolute" routerTag="a"
          linkTarget="_self" ncLinkType="link" ncOverflow="hidden" v-bind:visibility="true" activeClass=""
          ncTypography="body1" ncTooltipText=""
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'href','displayName':'Href'},{'type':'string','propName':'caption','displayName':'Caption'}]}"
          nucalScaleWidth="" toForRouterLink="to" exactActiveClass="" ncClickFontColor="#0000FF"
          ncFocusFontColor="#00FF00" ncHoverFontColor="#ff0000" nucalScaleHeight="" ncDisableFontColor="#4285f4"
          id="ac8907e0-6089-42b8-a521-d4d3902ababc"
          v-bind:style="{'color':'#4285f4','fontSize':'12px','maxWidth':'','minWidth':'','tabIndex':'-1','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1.4','marginLeft':'0px','paddingTop':'0px','textShadow':'','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none'}"/>
      </WBoxColorAdvertisement>
      <NucImage top="13.909774436090226%" left="46.446886446886445%" v-bind:snapX="false" v-bind:snapY="false" width=""
        height="" stretch="fill" imageUrl="https://demo.itportal.com/portal3/login/?rID=Logo&amp;Domain=&amp;cID="
        position="absolute" v-bind:isEnabled="true" v-bind:aspectRatio="true" dataLoading="static" ncTooltipText=""
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':true,'structure':[{'type':'string','update':{'type':'dataModelForDynamicType'},'propName':'imageUrl','displayName':'Value'}]}"
        nucalScaleWidth="0.174NS" nucalScaleHeight="0.079NS" ncClickBorderColor="black" ncHoverBorderColor="black"
        dataModelForDynamicType="string" id="f393c259-15fd-4ad2-b285-b3a637bb3fb8"
        v-bind:style="{'maxWidth':'','minWidth':'','boxShadow':'','marginTop':'0px','maxHeight':'','minHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','borderColor':'#4B74FF','borderStyle':'solid','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px'}"/>
      <WLabel top="27.694235588972433%" left="47.032967032967036%" text="myMSP's Portal!" v-bind:snapX="false"
        v-bind:snapY="false" theme="theme--light01" position="absolute" ncTypography="custom" ncTooltipText=""
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
        nucalScaleWidth="0.168NS" nucalScaleHeight="0.039NS" id="fe1fffde-5072-4413-8aa9-38400a1b7c55"
        v-bind:style="{'color':'#000000','fontSize':'24px','maxWidth':'','minWidth':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1.4','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none'}"/>
      <WInput id="c45a00ef-c4cb-4b84-b8f1-e8fe3804660a" top="34.962406015037594%" v-bind:lazy="false"
        left="44.83516483516483%" size="md" step="" text="" v-bind:trim="false" v-bind:snapX="false"
        v-bind:snapY="false" v-bind:noWheel="false" v-bind:disabled="false" position="absolute" v-bind:readonly="false"
        v-bind:required="false" wordList="" v-bind:autofocus="false" v-bind:plaintext="false" background=""
        ariaInvalid="false" v-bind:debounceVal="0" ncInputType="text" placeholder="Enter something..."
        v-bind:previewMode="true" autocomplete="" ncTypography="body1" v-bind:lazyFormatter="false" ncTooltipText=""
        v-bind:isWordListOpen="false"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':true,'structure':[{'type':'string','ncKey':'type','ncType':{'ncInputType':'number'},'ncValue':'number','propName':'text','displayName':'Value','nsDefaultValue':'string'}]}"
        v-bind:isNumberConvert="false" nucalScaleWidth="0.202NS" ncClickFontColor="#434855" ncFocusFontColor="#434855"
        ncHoverFontColor="#434855" ncMaxNumberValue="100" ncMinNumberValue="0" nucalScaleHeight="0.048NS"
        ncClickBorderColor="#000000" ncDisableFontColor="#434855" ncFocusBorderColor="#000000"
        ncHoverBorderColor="#000000" ncDisableBorderColor="#000000" formatterFunctionName=""
        ncClickBackgroundColor="#ffffff" ncFocusBackgroundColor="#ffffff" ncHoverBackgroundColor="#ffffff"
        ncDisableBackgroundColor="#ffffff"
        v-bind:style="{'color':'','fontSize':'12px','maxWidth':'','minWidth':'158px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1','marginLeft':'0px','paddingTop':'0px','visibility':'visible','borderColor':'#D1D1D6','borderStyle':'solid','marginRight':'0px','paddingLeft':'10px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none'}"/>
      <WDefaultCheckbox top="41.228070175438596%" left="44.83516483516483%" size="md" label="I accept the terms and use"
        v-bind:plain="false" v-bind:snapX="false" v-bind:snapY="false" theme="theme--light01" v-bind:value="true"
        v-bind:inline="false" fontSize="14px" position="absolute" v-bind:autofocus="false" v-bind:isEnabled="true"
        textAlign="left" fontFamily="Roboto-Regular,Roboto" fontWeight="normal" ncTypography="custom"
        v-bind:indeterminate="false" labelPosition="right" ncTooltipText="" v-bind:checkboxSwitch="false"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'boolean','propName':'value','displayName':'Value'},{'type':'string','propName':'label','displayName':'Display'}]}"
        nucalScaleWidth="" ncFocusFontColor="black" ncHoverFontColor="black" nucalScaleHeight=""
        ncDisableFontColor="black" ncFocusBorderColor="black" ncHoverBorderColor="black" ncDisableBorderColor="black"
        ncFocusBackgroundColor="transparent" ncHoverBackgroundColor="transparent" ncDisableBackgroundColor="transparent"
        id="526dbed8-19cf-4265-ac7c-4d34882724d1"
        v-bind:style="{'color':'','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'none','marginTop':'0px','maxHeight':'','minHeight':'','lineHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none'}"/>
      <WButton tag="button" top="45.48872180451128%" left="60.366300366300365%" v-bind:pill="false" size="md"
        text="Button" type="button" v-bind:block="false" color="" v-bind:snapX="false" v-bind:snapY="false"
        theme="theme--light01" v-bind:squared="false" variant="primary" position="absolute" v-bind:isEnabled="true"
        background="" borderColor="" ncTypography="body1" v-bind:resetTrigger="false" ncTooltipText=""
        verticalWidth="60px"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
        textDecoration="none" verticalHeight="60px" horizontalWidth="72.4479px" nucalScaleWidth=""
        horizontalHeight="37.5347px" ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF"
        nucalScaleHeight="" ncClickBorderColor="#4285f4" ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#4285f4"
        ncHoverBorderColor="#4285f4" ncDisableBorderColor="transparent" ncClickBackgroundColor="#4285f4"
        ncFocusBackgroundColor="#4285f4" ncHoverBackgroundColor="#4285f4" ncDisableBackgroundColor="#969696"
        id="eea79117-71a1-4fb1-8ab7-1c1210fd13fa"
        v-bind:style="{'width':'','height':'','fontSize':'12px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'','maxHeight':'','minHeight':'','textAlign':'center','fontFamily':'OpenSans-Bold,Open Sans','fontWeight':'normal','lineHeight':'1.4','marginLeft':'','paddingTop':'','textShadow':'','visibility':'visible','borderStyle':'solid','marginRight':'','paddingLeft':'','marginBottom':'','paddingRight':'','paddingBottom':'','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','horizontalHeight':'37.5347px','borderBottomWidth':'1px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px'}"/>
      <WLink top="56.766917293233085%" href="" left="44.395604395604394%" v-bind:exact="false" v-bind:snapX="false"
        v-bind:snapY="false" v-bind:active="false" v-bind:append="false" caption="Forgot Username?"
        v-bind:disabled="false" position="absolute" routerTag="a" linkTarget="_self" ncLinkType="link"
        ncOverflow="hidden" v-bind:visibility="true" activeClass="" ncTypography="body1" ncTooltipText=""
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'href','displayName':'Href'},{'type':'string','propName':'caption','displayName':'Caption'}]}"
        nucalScaleWidth="" toForRouterLink="to" exactActiveClass="" ncClickFontColor="#0000FF"
        ncFocusFontColor="#00FF00" ncHoverFontColor="#ff0000" nucalScaleHeight="" ncDisableFontColor="#4285f4"
        id="f8a9e94f-ca40-4af1-b735-5dc5858bd8dc"
        v-bind:style="{'color':'#4285f4','fontSize':'12px','maxWidth':'','minWidth':'','tabIndex':'-1','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1.4','marginLeft':'0px','paddingTop':'0px','textShadow':'','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none'}"/>
      <WLink top="54.26065162907268%" href="" left="44.24908424908425%" v-bind:exact="false" v-bind:snapX="false"
        v-bind:snapY="false" v-bind:active="false" v-bind:append="false" caption="Forgot password?"
        v-bind:disabled="false" position="absolute" routerTag="a" linkTarget="_self" ncLinkType="link"
        ncOverflow="hidden" v-bind:visibility="true" activeClass="" ncTypography="body1" ncTooltipText=""
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'href','displayName':'Href'},{'type':'string','propName':'caption','displayName':'Caption'}]}"
        nucalScaleWidth="" toForRouterLink="to" exactActiveClass="" ncClickFontColor="#0000FF"
        ncFocusFontColor="#00FF00" ncHoverFontColor="#ff0000" nucalScaleHeight="" ncDisableFontColor="#4285f4"
        id="57fadf20-08e2-49f1-a81f-169d5df79912"
        v-bind:style="{'color':'#4285f4','fontSize':'12px','maxWidth':'','minWidth':'','tabIndex':'-1','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1.4','marginLeft':'0px','paddingTop':'0px','textShadow':'','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none'}"/>
    </NucGridCell>
  </NucGridPage>
</template>
<script>
export default {
  name: 'ForgetPassword',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: {},
  methods: {},
  watch: {},
};
</script>

<style scoped></style>
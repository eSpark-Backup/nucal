<template>
  <NucGridPage v-bind:gap="{'col':0,'row':0}" v-bind:rows="[1]"
    v-bind:schema="{'r0-c0':{'col':0,'row':0,'showIn':['xs','sm','md','lg'],'colSpan':1,'rowSpan':1}}"
    v-bind:columns="[1]" overflow="auto" v-bind:designMode="false" v-bind:minNsLimit="158"
    v-bind:style="{'background':'#e6e6e6','paddingTop':'0px','paddingLeft':'0px','paddingRight':'0px','paddingBottom':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="9698ffbf-0b66-4d79-b2ad-4f5a6bcbf763" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <WBoxColorAdvertisement top="25.06265664160401%" left="40.21978021978022%" name="b-card" v-bind:blank="true"
        v-bind:snapX="false" v-bind:snapY="false" imgSrc="" v-bind:overlay="true" cardText="" position="absolute"
        bgVariant="primary" changeColor="#FFFFFF" textVariant="white"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'imgSrc','displayName':'ImageUrl'},{'type':'string','propName':'cardText','displayName':'Value'}]}"
        nucalScaleWidth="0.301NS" nucalScaleHeight="0.345NS" verticalPosition="align-items-center"
        horizontalPosition="justify-content-center" id="0cb6fbf0-99bb-4f66-aff8-0851be828754"
        v-bind:style="{'maxWidth':'','minWidth':'','marginTop':'0px','maxHeight':'','minHeight':'','marginLeft':'0px','paddingTop':'0px','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px'}">
        <NucInput top="16.83461502825906%" left="23.208062369271726%" text="" theme="theme--light01" maximum="100"
          minimum="0" position="absolute" tabIndex="0" isEnabled="Enable" v-bind:isMasking="false" ncInputType="text"
          placeholder="" v-bind:previewMode="true" ncTypography="body1" ncTooltipText=""
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':true,'structure':[{'type':'string','ncKey':'type','ncType':{'ncInputType':'number'},'ncValue':'number','propName':'text','displayName':'Value','nsDefaultValue':'string'}]}"
          nucalScaleWidth="" ncClickFontColor="#434855" ncFocusFontColor="#434855" ncHoverFontColor="#434855"
          nucalScaleHeight="" ncClickBorderColor="#000000" ncDisableFontColor="#434855" ncFocusBorderColor="#000000"
          ncHoverBorderColor="#000000" ncDisableBorderColor="#000000" ncClickBackgroundColor="#ffffff"
          ncFocusBackgroundColor="#ffffff" ncHoverBackgroundColor="#ffffff" ncDisableBackgroundColor="#ffffff"
          id="13c07038-68db-4147-8731-7c1915c365f4"
          v-bind:style="{'color':'#000000','fontSize':'12px','maxWidth':'','minWidth':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','background':'#FFFFFF','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1','marginLeft':'0px','paddingTop':'0px','visibility':'visible','borderColor':'#D1D1D6','borderStyle':'solid','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','borderBottomWidth':'1px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px'}"/>
        <WEmailInput id="99d99841-9fef-4cef-8be5-003162405315" top="18.014639117946817%" v-bind:lazy="false"
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
          v-bind:isButtonContentOpen="false" id="4417f869-dc4d-422e-ad18-780f10e18ebb"
          v-bind:style="{'color':'#000000','width':'','fontSize':'16px','maxWidth':'','minWidth':'','fontStyle':'normal','marginTop':'','maxHeight':'','minHeight':'','textAlign':'center','background':'#ffffff','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','marginLeft':'','paddingTop':'','visibility':'visible','marginRight':'','paddingLeft':'','marginBottom':'','paddingRight':'','paddingBottom':'','textDecoration':'none'}"/>
        <WPrimaryDropdown top="62.887179962321255%" v-bind:lazy="false" left="52.40425936489827%" role="menu" size="md"
          text="Primary" type="simple" v-bind:block="false" v-bind:right="false" theme="theme--light01"
          v-bind:noFlip="false" offset="0" v-bind:noCaret="false" v-bind:options="[]" splitTo="" variant="primary"
          position="absolute" v-bind:selected="[]" dataModel="" v-bind:isEnabled="true" splitHref=""
          visibility="visible" dataLoading="" v-bind:splitButton="false" ncTypography="body1" splitVariant=""
          buttonContent="" dataModelType="" ncTooltipText="" variantOfItem=""
          v-bind:nucalDataModel="{'type':'NSW','isList':true,'update':{'dataModel':'dataModel'},'dynamic':true,'dataModel':'','structure':[{'type':'','update':{'type':'dataModelType','dataModel':'dataModel'},'propName':'options','dataModel':'','displayName':'Value'}]}"
          dropdownOptions="" nucalScaleWidth="" splitButtonType="button" nucalScaleHeight=""
          v-bind:isButtonContentOpen="false" id="ec934785-56c4-4af9-b6e7-7e95d06a6632"
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
          ncDisableBackgroundColor="transparent" id="fe18ca99-2841-4fa2-b786-e9c734af74c3"
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
          id="2a44beca-1ea9-44db-9a47-b76a94956476"
          v-bind:style="{'width':'','height':'','fontSize':'12px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'','maxHeight':'','minHeight':'','textAlign':'center','fontFamily':'OpenSans-Bold,Open Sans','fontWeight':'normal','lineHeight':'1.4','marginLeft':'','paddingTop':'','textShadow':'','visibility':'visible','borderStyle':'solid','marginRight':'','paddingLeft':'','marginBottom':'','paddingRight':'','paddingBottom':'','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','horizontalHeight':'37.5347px','borderBottomWidth':'1px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px'}"/>
        <WLink top="76.92294388338121%" href="" left="18.58912340749192%" v-bind:exact="false" v-bind:active="false"
          v-bind:append="false" caption="Link" v-bind:disabled="false" position="absolute" routerTag="a"
          linkTarget="_self" ncLinkType="link" ncOverflow="hidden" v-bind:visibility="true" activeClass=""
          ncTypography="body1" ncTooltipText=""
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'href','displayName':'Href'},{'type':'string','propName':'caption','displayName':'Caption'}]}"
          nucalScaleWidth="" toForRouterLink="to" exactActiveClass="" ncClickFontColor="#0000FF"
          ncFocusFontColor="#00FF00" ncHoverFontColor="#ff0000" nucalScaleHeight="" ncDisableFontColor="#4285f4"
          id="4a714e22-f5c0-42f8-bcf9-3da563595693"
          v-bind:style="{'color':'#4285f4','fontSize':'12px','maxWidth':'','minWidth':'','tabIndex':'-1','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1.4','marginLeft':'0px','paddingTop':'0px','textShadow':'','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none'}"/>
      </WBoxColorAdvertisement>
      <NucImage top="13.659147869674186%" left="48.64468864468864%" v-bind:snapX="false" v-bind:snapY="false" width=""
        height="" stretch="fill" imageUrl="https://demo.itportal.com/portal3/login/?rID=Logo&amp;Domain=&amp;cID="
        position="absolute" v-bind:isEnabled="true" v-bind:aspectRatio="true" dataLoading="static" ncTooltipText=""
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':true,'structure':[{'type':'string','update':{'type':'dataModelForDynamicType'},'propName':'imageUrl','displayName':'Value'}]}"
        nucalScaleWidth="0.174NS" nucalScaleHeight="0.079NS" ncClickBorderColor="black" ncHoverBorderColor="black"
        dataModelForDynamicType="string" id="b72cfcd2-9757-4ad0-8bf4-12a3dd1cfafd"
        v-bind:style="{'maxWidth':'','minWidth':'','boxShadow':'','marginTop':'0px','maxHeight':'','minHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','borderColor':'#4B74FF','borderStyle':'solid','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px'}"/>
      <WLabel top="27.694235588972433%" left="47.032967032967036%" text="myMSP's Portal!" v-bind:snapX="false"
        v-bind:snapY="false" theme="theme--light01" position="absolute" ncTypography="custom" ncTooltipText=""
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
        nucalScaleWidth="0.168NS" nucalScaleHeight="0.039NS" id="cdc3d42e-c7eb-48ba-82fc-ea0ca3d877f0"
        v-bind:style="{'color':'#000000','fontSize':'24px','maxWidth':'','minWidth':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1.4','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none'}"/>
      <WInput id="1a726d56-58cc-4997-b23b-86c737511007" top="34.962406015037594%" v-bind:lazy="false"
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
      <WDefaultCheckbox top="41.60401002506266%" left="45.201465201465204%" size="md" label="I accept the terms and use"
        v-bind:plain="false" v-bind:snapX="false" v-bind:snapY="false" theme="theme--light01" v-bind:value="true"
        v-bind:inline="false" fontSize="14px" position="absolute" v-bind:autofocus="false" v-bind:isEnabled="true"
        textAlign="left" fontFamily="Roboto-Regular,Roboto" fontWeight="normal" ncTypography="custom"
        v-bind:indeterminate="false" labelPosition="right" ncTooltipText="" v-bind:checkboxSwitch="false"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'boolean','propName':'value','displayName':'Value'},{'type':'string','propName':'label','displayName':'Display'}]}"
        nucalScaleWidth="" ncFocusFontColor="black" ncHoverFontColor="black" nucalScaleHeight=""
        ncDisableFontColor="black" ncFocusBorderColor="black" ncHoverBorderColor="black" ncDisableBorderColor="black"
        ncFocusBackgroundColor="transparent" ncHoverBackgroundColor="transparent" ncDisableBackgroundColor="transparent"
        id="1668b743-6e5d-4a76-988d-bd8a5b9d6053"
        v-bind:style="{'color':'','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'none','marginTop':'0px','maxHeight':'','minHeight':'','lineHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none'}"/>
      <WButton tag="button" top="46.2406015037594%" left="60.07326007326007%" v-bind:pill="false" size="md"
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
        id="55788048-d9f8-41d2-bc23-5b004b1a02dc"
        v-bind:style="{'width':'','height':'','fontSize':'12px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'','maxHeight':'','minHeight':'','textAlign':'center','fontFamily':'OpenSans-Bold,Open Sans','fontWeight':'normal','lineHeight':'1.4','marginLeft':'','paddingTop':'','textShadow':'','visibility':'visible','borderStyle':'solid','marginRight':'','paddingLeft':'','marginBottom':'','paddingRight':'','paddingBottom':'','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','horizontalHeight':'37.5347px','borderBottomWidth':'1px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px'}"/>
      <WLink top="54.26065162907268%" href="" left="45.05494505494506%" v-bind:exact="false" v-bind:snapX="false"
        v-bind:snapY="false" v-bind:active="false" v-bind:append="false" caption="Forgot Username?"
        v-bind:disabled="false" position="absolute" routerTag="a" linkTarget="_self" ncLinkType="link"
        ncOverflow="hidden" v-bind:visibility="true" activeClass="" ncTypography="body1" ncTooltipText=""
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'href','displayName':'Href'},{'type':'string','propName':'caption','displayName':'Caption'}]}"
        nucalScaleWidth="" toForRouterLink="to" exactActiveClass="" ncClickFontColor="#0000FF"
        ncFocusFontColor="#00FF00" ncHoverFontColor="#ff0000" nucalScaleHeight="" ncDisableFontColor="#4285f4"
        id="0f977f1e-c493-41d5-a35f-1c73b0420fc3"
        v-bind:style="{'color':'#4285f4','fontSize':'12px','maxWidth':'','minWidth':'','tabIndex':'-1','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1.4','marginLeft':'0px','paddingTop':'0px','textShadow':'','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none'}"/>
      <WLink top="51.62907268170426%" href="" left="45.05494505494506%" v-bind:exact="false" v-bind:snapX="false"
        v-bind:snapY="false" v-bind:active="false" v-bind:append="false" caption="Forgot password?"
        v-bind:disabled="false" position="absolute" routerTag="a" linkTarget="_self" ncLinkType="link"
        ncOverflow="hidden" v-bind:visibility="true" activeClass="" ncTypography="body1" ncTooltipText=""
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'href','displayName':'Href'},{'type':'string','propName':'caption','displayName':'Caption'}]}"
        nucalScaleWidth="" toForRouterLink="to" exactActiveClass="" ncClickFontColor="#0000FF"
        ncFocusFontColor="#00FF00" ncHoverFontColor="#ff0000" nucalScaleHeight="" ncDisableFontColor="#4285f4"
        id="f99f398e-a068-47e5-9829-67965153c0e7"
        v-bind:style="{'color':'#4285f4','fontSize':'12px','maxWidth':'','minWidth':'','tabIndex':'-1','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1.4','marginLeft':'0px','paddingTop':'0px','textShadow':'','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none'}"/>
    </NucGridCell>
  </NucGridPage>
</template>
<script>
export default {
  name: 'ForgetUsername',
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
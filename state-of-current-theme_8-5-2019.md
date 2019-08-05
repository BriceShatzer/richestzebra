### Location  

https://www.tumblr.com/customize/richestzebra?redirect_to=/settings/blog/richestzebra

### Custom Theme 
**Edit HTML:**  

*note: current yells about not being able to save due to the presents of non-https urls*

```
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<!--
    
        .                                  .o8       oooo               
      .o8                                 "888       `888               
    .o888oo oooo  oooo  ooo. .oo.  .oo.    888oooo.   888  oooo d8b     
      888   `888  `888  `888P"Y88bP"Y88b   d88' `88b  888  `888""8P     
      888    888   888   888   888   888   888   888  888   888         
      888 .  888   888   888   888   888   888   888  888   888     .o. 
      "888"  `V88V"V8P' o888o o888o o888o  `Y8bod8P' o888o d888b    Y8P

             tailored by brice shatzer ~ briceshatzer.com
                            
-->

<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en" lang="en">
<head>



<div align=center>
<a href="http://www.richestzebra.com"> <img src="https://raw.githubusercontent.com/BriceShatzer/richestzebra/master/richestzebraFINAL.jpg"> </a>
</div>
    <!-- DEFAULT VARIABLES -->
    <meta name="color:Background" content="#3b627e" />
    <meta name="font:Title" content="Arial" />
    <meta name="font:Body" content="Arial" />
    <meta name="font:Accent" content="Lucida Sans" />
    <meta name="if:Show People I Follow" content="1" />
    <meta name="if:Show Tags" content="1" />
    <meta name="if:Show Album Art on Audio Posts" content="1" />
    <meta name="text:Disqus Shortname" content="" />
    <meta name="image:Header" content="" />
    <meta name="image:Background" content="" />
    
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <title>{Title}{block:SearchPage}, Search results for: {SearchQuery}{/block:SearchPage}{block:PostSummary}, {PostSummary}{/block:PostSummary}</title>
    {block:Description}<meta name="description" content="{MetaDescription}" />{/block:Description}
    <link rel="shortcut icon" href="{Favicon}" />
    <link rel="apple-touch-icon" href="{PortraitURL-128}"/>
    <link rel="alternate" type="application/rss+xml" href="{RSS}" />
    <link href="//maxcdn.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css" rel="stylesheet">
    <script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js"></script>
    <script src="http://ajax.googleapis.com/ajax/libs/jqueryui/1.9.2/jquery-ui.min.js"></script>
    <style type="text/css">
    /*! jQuery UI - v1.9.2 - 2012-12-11
    * http://jqueryui.com
    * Includes: jquery.ui.core.css, jquery.ui.accordion.css
    * To view and modify this theme, visit http://jqueryui.com/themeroller/?ffDefault=inherit&fwDefault=normal&fsDefault=&cornerRadius=3px&bgColorHeader=ffffff&bgTextureHeader=12_gloss_wave.png&bgImgOpacityHeader=5&borderColorHeader=666666&fcHeader=000000&iconColorHeader=000000&bgColorContent=ffffff&bgTextureContent=03_highlight_soft.png&bgImgOpacityContent=100&borderColorContent=666666&fcContent=000000&iconColorContent=000000&bgColorDefault=000000&bgTextureDefault=03_highlight_soft.png&bgImgOpacityDefault=5&borderColorDefault=000000&fcDefault=ffffff&iconColorDefault=ffffff&bgColorHover=ffffff&bgTextureHover=03_highlight_soft.png&bgImgOpacityHover=5&borderColorHover=666666&fcHover=000000&iconColorHover=000000&bgColorActive=ffffff&bgTextureActive=03_highlight_soft.png&bgImgOpacityActive=35&borderColorActive=000000&fcActive=000000&iconColorActive=000000&bgColorHighlight=ffffff&bgTextureHighlight=03_highlight_soft.png&bgImgOpacityHighlight=5&borderColorHighlight=666666&fcHighlight=000000&iconColorHighlight=000000&bgColorError=b81900&bgTextureError=08_diagonals_thick.png&bgImgOpacityError=18&borderColorError=cd0a0a&fcError=ffffff&iconColorError=ffd27a&bgColorOverlay=666666&bgTextureOverlay=08_diagonals_thick.png&bgImgOpacityOverlay=20&opacityOverlay=50&bgColorShadow=000000&bgTextureShadow=01_flat.png&bgImgOpacityShadow=10&opacityShadow=20&thicknessShadow=5px&offsetTopShadow=-5px&offsetLeftShadow=-5px&cornerRadiusShadow=5px
    * Copyright (c) 2012 jQuery Foundation and other contributors Licensed MIT */

    /* Layout helpers
    ----------------------------------*/
    .ui-helper-hidden { display: none; }
    .ui-helper-hidden-accessible { border: 0; clip: rect(0 0 0 0); height: 1px; margin: -1px; overflow: hidden; padding: 0; position: absolute; width: 1px; }
    .ui-helper-reset { margin: 0; padding: 0; border: 0; outline: 0; line-height: 1.3; text-decoration: none; font-size: 100%; list-style: none; }
    .ui-helper-clearfix:before, .ui-helper-clearfix:after { content: ""; display: table; }
    .ui-helper-clearfix:after { clear: both; }
    .ui-helper-clearfix { zoom: 1; }
    .ui-helper-zfix { width: 100%; height: 100%; top: 0; left: 0; position: absolute; opacity: 0; filter:Alpha(Opacity=0); }


    /* Interaction Cues
    ----------------------------------*/
    .ui-state-disabled { cursor: default !important; }


    /* Icons
    ----------------------------------*/

    /* states and images */
    .ui-icon { display: block; text-indent: -99999px; overflow: hidden; background-repeat: no-repeat; }


    /* Misc visuals
    ----------------------------------*/

    /* Overlays */
    .ui-widget-overlay { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }
    .ui-accordion .ui-accordion-header { display: block; cursor: pointer; position: relative; margin-top: 2px; padding: .5em .5em .5em .7em; zoom: 1; }
    .ui-accordion .ui-accordion-icons { padding-left: 2.2em; }
    .ui-accordion .ui-accordion-noicons { padding-left: .7em; }
    .ui-accordion .ui-accordion-icons .ui-accordion-icons { padding-left: 2.2em; }
    .ui-accordion .ui-accordion-header .ui-accordion-header-icon { position: absolute; left: .5em; top: 50%; margin-top: -8px; }
    .ui-accordion .ui-accordion-content { padding: 1em 2.2em; border-top: 0; overflow: auto; zoom: 1; }

    /* Component containers
    ----------------------------------*/
    .ui-widget { font-family: inherit; font-size: ; }
    .ui-widget .ui-widget { font-size: 1em; }
    .ui-widget input, .ui-widget select, .ui-widget textarea, .ui-widget button { font-family: inherit; font-size: 1em; }
    .ui-widget-content { border: 1px solid #666666; background: #ffffff url(images/ui-bg_highlight-soft_100_ffffff_1x100.png) 50% top repeat-x; color: #000000; }
    .ui-widget-content a { color: #000000; }
    .ui-widget-header { border: 1px solid #666666; background: #ffffff url(images/ui-bg_gloss-wave_5_ffffff_500x100.png) 50% 50% repeat-x; color: #000000; font-weight: bold; }
    .ui-widget-header a { color: #000000; }

    /* Interaction states
    ----------------------------------*/
    .ui-state-default, .ui-widget-content .ui-state-default, .ui-widget-header .ui-state-default { border: 1px solid #000000; background: #000000 url(images/ui-bg_highlight-soft_5_000000_1x100.png) 50% 50% repeat-x; font-weight: normal; color: #ffffff; }
    .ui-state-default a, .ui-state-default a:link, .ui-state-default a:visited { color: #ffffff; text-decoration: none; }
    .ui-state-hover, .ui-widget-content .ui-state-hover, .ui-widget-header .ui-state-hover, .ui-state-focus, .ui-widget-content .ui-state-focus, .ui-widget-header .ui-state-focus { border: 1px solid #666666; background: #ffffff url(images/ui-bg_highlight-soft_5_ffffff_1x100.png) 50% 50% repeat-x; font-weight: normal; color: #000000; }
    .ui-state-hover a, .ui-state-hover a:hover, .ui-state-hover a:link, .ui-state-hover a:visited { color: #000000; text-decoration: none; }
    .ui-state-active, .ui-widget-content .ui-state-active, .ui-widget-header .ui-state-active { border: 1px solid #000000; background: #ffffff url(images/ui-bg_highlight-soft_35_ffffff_1x100.png) 50% 50% repeat-x; font-weight: normal; color: #000000; }
    .ui-state-active a, .ui-state-active a:link, .ui-state-active a:visited { color: #000000; text-decoration: none; }

    /* Interaction Cues
    ----------------------------------*/
    .ui-state-highlight, .ui-widget-content .ui-state-highlight, .ui-widget-header .ui-state-highlight  {border: 1px solid #666666; background: #ffffff url(images/ui-bg_highlight-soft_5_ffffff_1x100.png) 50% top repeat-x; color: #000000; }
    .ui-state-highlight a, .ui-widget-content .ui-state-highlight a,.ui-widget-header .ui-state-highlight a { color: #000000; }
    .ui-state-error, .ui-widget-content .ui-state-error, .ui-widget-header .ui-state-error {border: 1px solid #cd0a0a; background: #b81900 url(images/ui-bg_diagonals-thick_18_b81900_40x40.png) 50% 50% repeat; color: #ffffff; }
    .ui-state-error a, .ui-widget-content .ui-state-error a, .ui-widget-header .ui-state-error a { color: #ffffff; }
    .ui-state-error-text, .ui-widget-content .ui-state-error-text, .ui-widget-header .ui-state-error-text { color: #ffffff; }
    .ui-priority-primary, .ui-widget-content .ui-priority-primary, .ui-widget-header .ui-priority-primary { font-weight: bold; }
    .ui-priority-secondary, .ui-widget-content .ui-priority-secondary,  .ui-widget-header .ui-priority-secondary { opacity: .7; filter:Alpha(Opacity=70); font-weight: normal; }
    .ui-state-disabled, .ui-widget-content .ui-state-disabled, .ui-widget-header .ui-state-disabled { opacity: .35; filter:Alpha(Opacity=35); background-image: none; }
    .ui-state-disabled .ui-icon { filter:Alpha(Opacity=35); } /* For IE8 - See #6059 */

    /* Icons
    ----------------------------------*/

    /* states and images */
    .ui-icon { width: 16px; height: 16px; background-image: url(images/ui-icons_000000_256x240.png); }
    .ui-widget-content .ui-icon {background-image: url(images/ui-icons_000000_256x240.png); }
    .ui-widget-header .ui-icon {background-image: url(images/ui-icons_000000_256x240.png); }
    .ui-state-default .ui-icon { background-image: url(images/ui-icons_ffffff_256x240.png); }
    .ui-state-hover .ui-icon, .ui-state-focus .ui-icon {background-image: url(images/ui-icons_000000_256x240.png); }
    .ui-state-active .ui-icon {background-image: url(images/ui-icons_000000_256x240.png); }
    .ui-state-highlight .ui-icon {background-image: url(images/ui-icons_000000_256x240.png); }
    .ui-state-error .ui-icon, .ui-state-error-text .ui-icon {background-image: url(images/ui-icons_ffd27a_256x240.png); }

    /* positioning */
    .ui-icon-carat-1-n { background-position: 0 0; }
    .ui-icon-carat-1-ne { background-position: -16px 0; }
    .ui-icon-carat-1-e { background-position: -32px 0; }
    .ui-icon-carat-1-se { background-position: -48px 0; }
    .ui-icon-carat-1-s { background-position: -64px 0; }
    .ui-icon-carat-1-sw { background-position: -80px 0; }
    .ui-icon-carat-1-w { background-position: -96px 0; }
    .ui-icon-carat-1-nw { background-position: -112px 0; }
    .ui-icon-carat-2-n-s { background-position: -128px 0; }
    .ui-icon-carat-2-e-w { background-position: -144px 0; }
    .ui-icon-triangle-1-n { background-position: 0 -16px; }
    .ui-icon-triangle-1-ne { background-position: -16px -16px; }
    .ui-icon-triangle-1-e { background-position: -32px -16px; }
    .ui-icon-triangle-1-se { background-position: -48px -16px; }
    .ui-icon-triangle-1-s { background-position: -64px -16px; }
    .ui-icon-triangle-1-sw { background-position: -80px -16px; }
    .ui-icon-triangle-1-w { background-position: -96px -16px; }
    .ui-icon-triangle-1-nw { background-position: -112px -16px; }
    .ui-icon-triangle-2-n-s { background-position: -128px -16px; }
    .ui-icon-triangle-2-e-w { background-position: -144px -16px; }
    .ui-icon-arrow-1-n { background-position: 0 -32px; }
    .ui-icon-arrow-1-ne { background-position: -16px -32px; }
    .ui-icon-arrow-1-e { background-position: -32px -32px; }
    .ui-icon-arrow-1-se { background-position: -48px -32px; }
    .ui-icon-arrow-1-s { background-position: -64px -32px; }
    .ui-icon-arrow-1-sw { background-position: -80px -32px; }
    .ui-icon-arrow-1-w { background-position: -96px -32px; }
    .ui-icon-arrow-1-nw { background-position: -112px -32px; }
    .ui-icon-arrow-2-n-s { background-position: -128px -32px; }
    .ui-icon-arrow-2-ne-sw { background-position: -144px -32px; }
    .ui-icon-arrow-2-e-w { background-position: -160px -32px; }
    .ui-icon-arrow-2-se-nw { background-position: -176px -32px; }
    .ui-icon-arrowstop-1-n { background-position: -192px -32px; }
    .ui-icon-arrowstop-1-e { background-position: -208px -32px; }
    .ui-icon-arrowstop-1-s { background-position: -224px -32px; }
    .ui-icon-arrowstop-1-w { background-position: -240px -32px; }
    .ui-icon-arrowthick-1-n { background-position: 0 -48px; }
    .ui-icon-arrowthick-1-ne { background-position: -16px -48px; }
    .ui-icon-arrowthick-1-e { background-position: -32px -48px; }
    .ui-icon-arrowthick-1-se { background-position: -48px -48px; }
    .ui-icon-arrowthick-1-s { background-position: -64px -48px; }
    .ui-icon-arrowthick-1-sw { background-position: -80px -48px; }
    .ui-icon-arrowthick-1-w { background-position: -96px -48px; }
    .ui-icon-arrowthick-1-nw { background-position: -112px -48px; }
    .ui-icon-arrowthick-2-n-s { background-position: -128px -48px; }
    .ui-icon-arrowthick-2-ne-sw { background-position: -144px -48px; }
    .ui-icon-arrowthick-2-e-w { background-position: -160px -48px; }
    .ui-icon-arrowthick-2-se-nw { background-position: -176px -48px; }
    .ui-icon-arrowthickstop-1-n { background-position: -192px -48px; }
    .ui-icon-arrowthickstop-1-e { background-position: -208px -48px; }
    .ui-icon-arrowthickstop-1-s { background-position: -224px -48px; }
    .ui-icon-arrowthickstop-1-w { background-position: -240px -48px; }
    .ui-icon-arrowreturnthick-1-w { background-position: 0 -64px; }
    .ui-icon-arrowreturnthick-1-n { background-position: -16px -64px; }
    .ui-icon-arrowreturnthick-1-e { background-position: -32px -64px; }
    .ui-icon-arrowreturnthick-1-s { background-position: -48px -64px; }
    .ui-icon-arrowreturn-1-w { background-position: -64px -64px; }
    .ui-icon-arrowreturn-1-n { background-position: -80px -64px; }
    .ui-icon-arrowreturn-1-e { background-position: -96px -64px; }
    .ui-icon-arrowreturn-1-s { background-position: -112px -64px; }
    .ui-icon-arrowrefresh-1-w { background-position: -128px -64px; }
    .ui-icon-arrowrefresh-1-n { background-position: -144px -64px; }
    .ui-icon-arrowrefresh-1-e { background-position: -160px -64px; }
    .ui-icon-arrowrefresh-1-s { background-position: -176px -64px; }
    .ui-icon-arrow-4 { background-position: 0 -80px; }
    .ui-icon-arrow-4-diag { background-position: -16px -80px; }
    .ui-icon-extlink { background-position: -32px -80px; }
    .ui-icon-newwin { background-position: -48px -80px; }
    .ui-icon-refresh { background-position: -64px -80px; }
    .ui-icon-shuffle { background-position: -80px -80px; }
    .ui-icon-transfer-e-w { background-position: -96px -80px; }
    .ui-icon-transferthick-e-w { background-position: -112px -80px; }
    .ui-icon-folder-collapsed { background-position: 0 -96px; }
    .ui-icon-folder-open { background-position: -16px -96px; }
    .ui-icon-document { background-position: -32px -96px; }
    .ui-icon-document-b { background-position: -48px -96px; }
    .ui-icon-note { background-position: -64px -96px; }
    .ui-icon-mail-closed { background-position: -80px -96px; }
    .ui-icon-mail-open { background-position: -96px -96px; }
    .ui-icon-suitcase { background-position: -112px -96px; }
    .ui-icon-comment { background-position: -128px -96px; }
    .ui-icon-person { background-position: -144px -96px; }
    .ui-icon-print { background-position: -160px -96px; }
    .ui-icon-trash { background-position: -176px -96px; }
    .ui-icon-locked { background-position: -192px -96px; }
    .ui-icon-unlocked { background-position: -208px -96px; }
    .ui-icon-bookmark { background-position: -224px -96px; }
    .ui-icon-tag { background-position: -240px -96px; }
    .ui-icon-home { background-position: 0 -112px; }
    .ui-icon-flag { background-position: -16px -112px; }
    .ui-icon-calendar { background-position: -32px -112px; }
    .ui-icon-cart { background-position: -48px -112px; }
    .ui-icon-pencil { background-position: -64px -112px; }
    .ui-icon-clock { background-position: -80px -112px; }
    .ui-icon-disk { background-position: -96px -112px; }
    .ui-icon-calculator { background-position: -112px -112px; }
    .ui-icon-zoomin { background-position: -128px -112px; }
    .ui-icon-zoomout { background-position: -144px -112px; }
    .ui-icon-search { background-position: -160px -112px; }
    .ui-icon-wrench { background-position: -176px -112px; }
    .ui-icon-gear { background-position: -192px -112px; }
    .ui-icon-heart { background-position: -208px -112px; }
    .ui-icon-star { background-position: -224px -112px; }
    .ui-icon-link { background-position: -240px -112px; }
    .ui-icon-cancel { background-position: 0 -128px; }
    .ui-icon-plus { background-position: -16px -128px; }
    .ui-icon-plusthick { background-position: -32px -128px; }
    .ui-icon-minus { background-position: -48px -128px; }
    .ui-icon-minusthick { background-position: -64px -128px; }
    .ui-icon-close { background-position: -80px -128px; }
    .ui-icon-closethick { background-position: -96px -128px; }
    .ui-icon-key { background-position: -112px -128px; }
    .ui-icon-lightbulb { background-position: -128px -128px; }
    .ui-icon-scissors { background-position: -144px -128px; }
    .ui-icon-clipboard { background-position: -160px -128px; }
    .ui-icon-copy { background-position: -176px -128px; }
    .ui-icon-contact { background-position: -192px -128px; }
    .ui-icon-image { background-position: -208px -128px; }
    .ui-icon-video { background-position: -224px -128px; }
    .ui-icon-script { background-position: -240px -128px; }
    .ui-icon-alert { background-position: 0 -144px; }
    .ui-icon-info { background-position: -16px -144px; }
    .ui-icon-notice { background-position: -32px -144px; }
    .ui-icon-help { background-position: -48px -144px; }
    .ui-icon-check { background-position: -64px -144px; }
    .ui-icon-bullet { background-position: -80px -144px; }
    .ui-icon-radio-on { background-position: -96px -144px; }
    .ui-icon-radio-off { background-position: -112px -144px; }
    .ui-icon-pin-w { background-position: -128px -144px; }
    .ui-icon-pin-s { background-position: -144px -144px; }
    .ui-icon-play { background-position: 0 -160px; }
    .ui-icon-pause { background-position: -16px -160px; }
    .ui-icon-seek-next { background-position: -32px -160px; }
    .ui-icon-seek-prev { background-position: -48px -160px; }
    .ui-icon-seek-end { background-position: -64px -160px; }
    .ui-icon-seek-start { background-position: -80px -160px; }
    /* ui-icon-seek-first is deprecated, use ui-icon-seek-start instead */
    .ui-icon-seek-first { background-position: -80px -160px; }
    .ui-icon-stop { background-position: -96px -160px; }
    .ui-icon-eject { background-position: -112px -160px; }
    .ui-icon-volume-off { background-position: -128px -160px; }
    .ui-icon-volume-on { background-position: -144px -160px; }
    .ui-icon-power { background-position: 0 -176px; }
    .ui-icon-signal-diag { background-position: -16px -176px; }
    .ui-icon-signal { background-position: -32px -176px; }
    .ui-icon-battery-0 { background-position: -48px -176px; }
    .ui-icon-battery-1 { background-position: -64px -176px; }
    .ui-icon-battery-2 { background-position: -80px -176px; }
    .ui-icon-battery-3 { background-position: -96px -176px; }
    .ui-icon-circle-plus { background-position: 0 -192px; }
    .ui-icon-circle-minus { background-position: -16px -192px; }
    .ui-icon-circle-close { background-position: -32px -192px; }
    .ui-icon-circle-triangle-e { background-position: -48px -192px; }
    .ui-icon-circle-triangle-s { background-position: -64px -192px; }
    .ui-icon-circle-triangle-w { background-position: -80px -192px; }
    .ui-icon-circle-triangle-n { background-position: -96px -192px; }
    .ui-icon-circle-arrow-e { background-position: -112px -192px; }
    .ui-icon-circle-arrow-s { background-position: -128px -192px; }
    .ui-icon-circle-arrow-w { background-position: -144px -192px; }
    .ui-icon-circle-arrow-n { background-position: -160px -192px; }
    .ui-icon-circle-zoomin { background-position: -176px -192px; }
    .ui-icon-circle-zoomout { background-position: -192px -192px; }
    .ui-icon-circle-check { background-position: -208px -192px; }
    .ui-icon-circlesmall-plus { background-position: 0 -208px; }
    .ui-icon-circlesmall-minus { background-position: -16px -208px; }
    .ui-icon-circlesmall-close { background-position: -32px -208px; }
    .ui-icon-squaresmall-plus { background-position: -48px -208px; }
    .ui-icon-squaresmall-minus { background-position: -64px -208px; }
    .ui-icon-squaresmall-close { background-position: -80px -208px; }
    .ui-icon-grip-dotted-vertical { background-position: 0 -224px; }
    .ui-icon-grip-dotted-horizontal { background-position: -16px -224px; }
    .ui-icon-grip-solid-vertical { background-position: -32px -224px; }
    .ui-icon-grip-solid-horizontal { background-position: -48px -224px; }
    .ui-icon-gripsmall-diagonal-se { background-position: -64px -224px; }
    .ui-icon-grip-diagonal-se { background-position: -80px -224px; }


    /* Misc visuals
    ----------------------------------*/

    /* Corner radius */
    .ui-corner-all, .ui-corner-top, .ui-corner-left, .ui-corner-tl { -moz-border-radius-topleft: 3px; -webkit-border-top-left-radius: 3px; -khtml-border-top-left-radius: 3px; border-top-left-radius: 3px; }
    .ui-corner-all, .ui-corner-top, .ui-corner-right, .ui-corner-tr { -moz-border-radius-topright: 3px; -webkit-border-top-right-radius: 3px; -khtml-border-top-right-radius: 3px; border-top-right-radius: 3px; }
    .ui-corner-all, .ui-corner-bottom, .ui-corner-left, .ui-corner-bl { -moz-border-radius-bottomleft: 3px; -webkit-border-bottom-left-radius: 3px; -khtml-border-bottom-left-radius: 3px; border-bottom-left-radius: 3px; }
    .ui-corner-all, .ui-corner-bottom, .ui-corner-right, .ui-corner-br { -moz-border-radius-bottomright: 3px; -webkit-border-bottom-right-radius: 3px; -khtml-border-bottom-right-radius: 3px; border-bottom-right-radius: 3px; }

    /* Overlays */
    .ui-widget-overlay { background: #666666 url(images/ui-bg_diagonals-thick_20_666666_40x40.png) 50% 50% repeat; opacity: .5;filter:Alpha(Opacity=50); }
    .ui-widget-shadow { margin: -5px 0 0 -5px; padding: 5px; background: #000000 url(images/ui-bg_flat_10_000000_40x100.png) 50% 50% repeat-x; opacity: .2;filter:Alpha(Opacity=20); -moz-border-radius: 5px; -khtml-border-radius: 5px; -webkit-border-radius: 5px; border-radius: 5px; }
        
    
    
    
    body {
            background: {color:Background} url('{image:Background}') top left fixed repeat;
            margin: 0;
            padding: 0;
            font-family: Arial, Helvetica, sans-serif;
        }
        
        .clear {
            clear: both;
            height: 0px;
            overflow: hidden;
        }
        
        a img {
            border: none;
        }
        #static_wrapper{padding:0 8px 6px 8px;}
        #hr{width:350px;margin:25px auto;}
        
        #wrapper {
            width: 845px;
            margin: 0 auto;
        }
        
            #wrapper #title {
                margin: 30px 0;
                color: #fff;
                font-size: 50px;
                font-weight: bold;
                font-family: Arial, Helvetica, sans-serif;
                text-shadow: #2f2f2f 1px 3px 5px;
                letter-spacing: -1px;
            }
            
                #wrapper #title a {
                    color: #fff;
                    text-decoration: none;
                }
            
            #wrapper #content {
                width: 520px;
                float: left;
            }
            
                #wrapper #content .post {
                    font-family: Arial, Helvetica, sans-serif;
                    background: #fff;
                    padding: 10px;
                    position: relative;
                }
                    
                    #wrapper #content .post .media {
                        text-align: center;
                        margin-bottom: 10px;
                    }
                    
                    #wrapper #content .post .quotebg {
                        font-family: georgia, serif;
                        font-size: 150px;
                        color: {color:Background};
                        opacity: 0.2;
                        filter: alpha(opacity=20);
                        -ms-filter:"progid:DXImageTransform.Microsoft.Alpha(Opacity=20)";
                        position: absolute;
                        top: 70px;
                        left: 10px;
                    }
                    
                    #wrapper #content .post .quote {
                        color: {color:Background};
                        font-weight: bold;
                        padding: 20px 20px 5px 20px;
                    }
                    
                    #wrapper #content .post .quote.short {
                        font-size: 33px;
                        line-height: 35px;
                    }
                    
                    #wrapper #content .post .quote.medium {
                        font-size: 25px;
                        line-height: 28px;
                    }
                    
                    #wrapper #content .post .quote.long {
                        font-size: 18px;
                        line-height: 22px;
                    }
                                        
                        #wrapper #content .post .quote_source *:first-child {
                            margin-top: 0px;
                        }
                        
                        #wrapper #content .post .quote_source *:last-child {
                            margin-bottom: 0px;
                        }
                        
                        #wrapper #content .post .quote *:first-child {
                            margin-top: 0px;
                        }
                        
                        #wrapper #content .post .quote *:last-child {
                            margin-bottom: 0px;
                        }
                        
                    #wrapper #content .post .copy {
                        color: #000000;
                        font-size: 13px;
                        line-height: 15px;
                    }
                        
                        #wrapper #content .post .copy a {
                            color: #000;
                            text-decoration: underline;
                        }
                        
                        #wrapper #content .post .copy p {
                            margin: 10px 0 0 0;
                            padding: 0 10px 0;
                        }
                        
                        #wrapper #content .post .copy pre {
                            margin: 10px 0px 10px 0px;
                            padding: 10px;
                            background-color: #e6e6e6;
                            font: normal 11px Courier, monospace;
                            overflow: auto;
                        }
                        
                        #wrapper #content .post .copy > p:first-child {
                            margin-top: 0;
                        }
                        
                        #wrapper #content .post .copy img {
                            max-width: 100%;
                        }
                    
                    #wrapper #content .post .audio {
                        background: #eaeaea;
                        float: left;
                        padding: 7px;
                        margin-bottom: 10px;
                        -moz-border-radius: 4px;
                        -webkit-border-radius: 4px;
                        border-radius: 4px;
                    }
                                                        
                        #wrapper #content .post .audio .player {
                            float: left;
                        }
                        
                            #wrapper #content .post .audio .player .audio_player embed {
                                border: 1px solid #c8c8c8;
                            }
                        
                        #wrapper #content .post .audio .meta {
                            padding: 8px 13px;
                            height: 13px;
                            float: left;
                            color: #666;
                            font-family: Arial, Helvetica, sans-serif;
                            font-size: 11px;
                        }
                        
                            #wrapper #content .post .audio .meta a {
                                color: #666;
                                text-decoration: none;
                            }
                    
                    #wrapper #content .post .album_art {
                        text-align: center;
                    }
                    
                    #wrapper #content .post .question {
                        color: #000000;
                        font-size: 16px;
                        font-weight: bold;
                        background: #f1f1f1;
                        -moz-border-radius: 8px;
                        -webkit-border-radius: 8px;
                        border-radius: 8px;
                        margin: 0 0 15px 0;
                        padding: 15px 20px;
                        position: relative;
                    }
                    
                        #wrapper #content .post .question .nipple {
                            width: 13px;
                            height: 7px;
                            background: #f1f1f1 url('http://static.tumblr.com/thpaaos/wqzkvsd69/mask_ask.png');
                            position: absolute;
                            bottom: -7px;
                            left: 30px;
                        }
                        
                    #wrapper #content .post .asker_container {
                        margin: 0 0 20px 24px;
                    }
                    
                        #wrapper #content .post .asker_container img {
                            margin: 0 12px -7px 0;
                        }
                        
                        #wrapper #content .post .asker_container a.asker {
                            color: {color:Body};
                        }
                    
                    #wrapper #content .post .title {
                        color: #000000;
                        font-size: 16px;
                        font-weight: bold;
                        padding: 5px 10px 10px 10px;
                    }
                    
                    #wrapper #content .post img {
                      max-width: 500px;
                    }
                                        
                    #wrapper #content .post .chat {
                        background-color: #fff;
                        border-left: 5px solid #dedddd;
                        margin: 10px 10px 0 10px;
                        font-size: 14px;
                    }
                                        
                        #wrapper #content .post .chat .lines {
                            margin-left: 1px;
                        }
                        
                            #wrapper #content .post .chat .lines .line {
                                background-color: #eaeaea;
                                color: #000000;
                                margin-bottom: 1px;
                                padding: 3px 5px;
                            }
                            
                            #wrapper #content .post .chat .lines .line.even {
                                background-color: #dedddd;
                            }
                        
                        #wrapper #content .post .link {
                            margin: 4px 0 2px 0;
                            font-size: 16px;
                            line-height: 25px;
                        }
                            
                            #wrapper #content .post .link a {
                                background-color: {color:Background};
                                color: #fff;
                                padding: 5px 7px;
                                -moz-border-radius: 4px;
                                -webkit-border-radius: 4px;
                                border-radius: 4px;
                            }
                            
                            #wrapper #content .post .link a:hover {
                                opacity: 0.9;
                                filter: alpha(opacity=90);
                                -ms-filter:"progid:DXImageTransform.Microsoft.Alpha(Opacity=90)";
                            }
                    
                    #wrapper #content .post .footer {
                        background: #eaeaea;
                        -moz-border-radius: 4px;
                        -webkit-border-radius: 4px;
                        border-radius: 4px;
                        font-family: Arial, Helvetica, sans-serif;
                        font-size: 11px;
                        color: #666;
                        padding: 5px 10px;
                        margin-top: 10px;
                    }
                        
                        #wrapper #content .post .footer:hover {
                            opacity: 0.9;
                            filter: alpha(opacity=90);
                            -ms-filter:"progid:DXImageTransform.Microsoft.Alpha(Opacity=90)";
                        }
                        
                        #wrapper #content .post .footer .date {
                            width: 67%;
                            float: left;
                            color: #666;
                        }
                        
                        #wrapper #content .post .footer .notes {
                            width: 33%;
                            float: right;
                            text-align: right;
                            color: #666;
                        }
                            
                            #wrapper #content .post .footer .notes a {
                                color: #666;
                            }
                            
                                                       
                           #wrapper #content .post .footer .tags a {
                                color: #4a4a51;
                                text-decoration: underline;
                            }
                            
                                #wrapper #content .post .footer .tags .tag-commas:last-child {
                                    display: none;
                                }
                        
                        #wrapper #content .post a {
                            color: #000;
                            text-decoration: none;
                        }
                        
                            #wrapper #content .post .copy blockquote {
                                margin: 10px 0px 10px 10px;
                                padding-left: 15px;
                                border-left: solid 4px #dcdcdc;
                            }
                            
                                #wrapper #content .post .copy blockquote blockquote {
                                    border-left: solid 4px #cccccc;
                                }
                                
                                    #wrapper #content .post .copy blockquote blockquote blockquote {
                                        border-left: solid 4px #bcbcbc;
                                    }
                                    
                                        #wrapper #content .post .copy blockquote blockquote blockquote blockquote {
                                            border-left: solid 4px #acacac;
                                        }
                                        
                                            #wrapper #content .post .copy blockquote blockquote blockquote blockquote blockquote {
                                                border-left: solid 4px #9c9c9c;
                                            }
                                            
                                                #wrapper #content .post .copy blockquote blockquote blockquote blockquote blockquote blockquote {
                                                    border-left: solid 4px #8c8c8c;
                                                }
                        
                        #wrapper #content .bottom {
                            background: url('http://assets.tumblr.com/themes/redux/shadow-post.png') top center no-repeat transparent;
                            width: 513px;
                            height: 40px;
                            margin: 0 auto;
                        }
                        
                        #wrapper #content #navigation {
                            text-align: right;
                            padding-bottom: 35px;
                        }
                        
                            #wrapper #content #navigation a {
                                background-color: #fff;
                                color: {color:Background};
                                padding: 5px 10px;
                                text-decoration: none;
                                margin-left: 25px;
                            }
                            
                            #wrapper #content #navigation a:hover {
                                opacity: 0.9;
                                filter: alpha(opacity=90);
                                -ms-filter:"progid:DXImageTransform.Microsoft.Alpha(Opacity=90)";
                            }
                            
                            #wrapper #content .post .notecontainer {
                                background: #eaeaea;
                                -moz-border-radius: 4px;
                                -webkit-border-radius: 4px;
                                border-radius: 4px;
                                font-family: Arial, Helvetica, sans-serif;
                                font-size: 11px;
                                color: #666;
                                margin-top: 10px;
                                margin-bottom: -10px;
                            }
                            
                                    #wrapper #content .post .notecontainer a {
                                        color: #666;
                                        text-decoration: underline;
                                    }
                                    
                                    #wrapper #content .post .notecontainer ol.notes {
                                        padding: 0px 0 10px 0;
                                        list-style-type: none;
                                        font-size: 11px;
                                    }
                                    
                                        #wrapper #content .post .notecontainer ol.notes li.note {
                                            padding: 10px 10px 0 10px;
                                        }
                                        
                                            #wrapper #content .post .notecontainer ol.notes li.note img.avatar {
                                                vertical-align: -4px;
                                                margin-right: 10px;
                                                width: 16px;
                                                height: 16px;
                                            }
                                            
                                            #wrapper #content .post .notecontainer ol.notes li.note span.action {
                                                font-weight: normal;
                                            }
                                            
                                            #wrapper #content .post .notecontainer ol.notes li.note .answer_content {
                                                font-weight: normal;
                                            }
                                            
                                            #wrapper #content .post .notecontainer ol.notes li.note blockquote {
                                                border-left: 2px solid #666;
                                                padding: 4px 10px;
                                                margin: 10px 0px 0px 25px;
                                            }
                                            
                                                #wrapper #content .post .notecontainer ol.notes li.note blockquote a {
                                                    text-decoration: none;
                                                }
                
                #wrapper #content #searchresults {
                    color: #fff;
                    margin: 0 0 15px 0;
                    text-shadow: #2f2f2f 1px 3px 5px;
                    font-family: Arial, Helvetica, sans-serif;
                    font-size: 20px;
                }
            
            #wrapper #sidebar {
                width: 250px;
                float: right;
                color: {color:Background};
                font-family: Arial, Helvetica, sans-serif;
            }
            
                #wrapper #sidebar a {
                    color: {color:Background};
                }
                
                #wrapper #sidebar #top {
                    background: #fff;
                    padding: 0 20px;
                    
                    -webkit-border-top-left-radius: 10px;
                    -webkit-border-top-right-radius: 10px;
                    -moz-border-radius-topleft: 10px;
                    -moz-border-radius-topright: 10px;
                    border-top-left-radius: 10px;
                    border-top-right-radius: 10px;
                }
                
              
                    }
                    
                    #wrapper #sidebar #top #pages {
                        margin-bottom: 15px;
                        font-size: 12px;
                    }
                    
                        #wrapper #sidebar #top #pages.ask_and_submit {
                            display: none;
                            {block:AskEnabled}display: block;{/block:AskEnabled}
                            {block:SubmissionsEnabled}display: block;{/block:SubmissionsEnabled}
                        }
                    
                        #wrapper #sidebar #top #pages a.page {
                            display: block;
                            background-color: {color:Background};
                            border:1px solid {color:Background};
                            color: #fff;
                            padding: 4px 5px;
                            margin: 0 0px 5px 0;
                            width:198px;
                            -webkit-border-radius: 3px;
                            -moz-border-radius: 3px;
                            border-radius: 3px;
                            transition: all 300ms ease-out;
                            -moz-transition: all 300ms ease-out;
                            -webkit-transition: all 300ms ease-out;
                            -o-transition: all 300ms ease-out;
                            
                        }
                        
                                               
                        #wrapper #sidebar #top #pages a.page:hover {
                            background-color:white;
                            color:black;
                            text-indent:33%;
                            transition: all 300ms ease-in;
                            -moz-transition: all 300ms ease-in;
                            -webkit-transition: all 300ms ease-in;
                            -o-transition: all 300ms ease-in;
                        }
                        
                    #wrapper #sidebar #top #description {
                        font-size: 11px;
                        position: relative;
                        top: -18px;
                    }
                    
                        #wrapper #sidebar #top #description a {
                            color: {color:Background};
                        }
                    
                    #wrapper #sidebar #top #search {
                        background: #fff;
                        border: 1px solid {color:Background};
                        -moz-border-radius: 4px;
                        -webkit-border-radius: 4px;
                        border-radius: 4px;
                        overflow:auto;
                    }
                    
                    #wrapper #sidebar #top #search-scope {
                        padding-top: 5px;
                        font-size: 11px;
                        text-align: center;
                    }
                    
                        #wrapper #sidebar #top #search-scope input,
                        #wrapper #sidebar #top #search-scope label {
                            cursor: pointer;
                        }
                        
                        #wrapper #sidebar #top #search form {
                            margin: 0;
                            padding:0 0 0 5px;
                        }
                            
                            #wrapper #sidebar #top #search form .query {
                                height:16px;
                                margin:0;
                                padding: 8px 0px;
                                font-family: Arial, Helvetica, sans-serif;
                                font-size:13px;
                                line-height:16px;
                                color:#666666;
                                border: none;
                                background: transparent;
                                outline: none;
                                width: 125px;
                                float: left;
                                color: {color:Background};
                            }
                            
                            #wrapper #sidebar #top #search form .submit {
                                background: {color:Background};
                                color: #fff;
                                border: none;
                                padding: 5px 7px;
                                float: right;
                                border:1px solid black; 
                                margin:2px 2px 2px 0;
                                -moz-border-radius: 3px;
                                -webkit-border-radius: 3px;
                                border-radius: 3px;
                                cursor: pointer;
                                transition: all 250ms ease-out;
                            -moz-transition: all 250ms ease-out;
                            -webkit-transition: all 250ms ease-out;
                            -o-transition: all 250ms ease-out;
                            }
                            
                            #wrapper #sidebar #top #search form .submit:hover {
                            background-color:white;
                            color:black;
                            border:1px solid black; 
                            margin:2px 2px 2px 0;
                            transition: all 250ms ease-in;
                            -moz-transition: all 250ms ease-in;
                            -webkit-transition: all 250ms ease-in;
                            -o-transition: all 250ms ease-in;
                            }
                    
                    #wrapper #sidebar #top .content {
                        margin-top: 2px;
                        padding: 7px 10px;
                        background: #eaeaea;
                        color: #666;
                        font-size: 11px;
                        overflow: hidden;
                    }
                    
                        #wrapper #sidebar #top a {
                            text-decoration: none;
                        }
                    
                        #wrapper #sidebar #top #following-avatars.content {
                            padding: 4px;
                        }
                    
                                #wrapper #sidebar #top #following-avatars.content a img {
                                    margin: 5px;
                                }
                                
                        #wrapper #sidebar #top #buttons {
                            padding: 20px 0 0 0;
                        }
                        
                            #wrapper #sidebar #top #buttons .button {
                                width: 35%;
                                height: 21px;
                                float: left;
                                background: left center no-repeat transparent;
                                padding: 2px 0 0 30px;
                                font-size: 14px;
                            }
                            
                                #wrapper #sidebar #top #buttons a {
                                    color: {color:Background};
                                    text-decoration: none;
                                }
                            
                                #wrapper #sidebar #top #buttons div {
                                    padding-bottom: 10px;
                                }
                            
                            #wrapper #sidebar #top #buttons .button#button-rss {
                                background-image: url('http://assets.tumblr.com/themes/redux/button-rss.png?2');
                            }
                            
                            #wrapper #sidebar #top #buttons .button#button-random {
                                background-image: url('http://assets.tumblr.com/themes/redux/button-random.png?2');
                            }
                            
                            #wrapper #sidebar #top #buttons .button#button-archive {
                                background-image: url('http://assets.tumblr.com/themes/redux/button-archive.png?2');
                            }
                            
                            #wrapper #sidebar #top #buttons .button#button-mobile {
                                background-image: url('http://assets.tumblr.com/themes/redux/button-mobile.png?2');
                            }
                
                    #wrapper #sidebar #bottom {
                        background: url('http://assets.tumblr.com/themes/redux/sidebar-bottom.png') top center no-repeat transparent;
                        width: 250px;
                        height: 25px;
                    }
                    
                    #wrapper #sidebar #copyright {
                        text-align: center;
                        color: #fff;
                        font-size: 12px;
                        margin-bottom: 10px;
                    }
                    
                        #wrapper #sidebar #copyright a {
                            color: #fff;
                            margin-left: 15px;
                        }
    
    </style>
    <!--[if lt IE 7.]>
        <style type="text/css">
            #wrapper #sidebar #bottom {
                background: transparent;
            }
            
            #wrapper #sidebar #top #avatar {
                background: none;
            }
            
            #wrapper #sidebar #top #avatar img {
                border: 5px solid #f1f1f1;
            }
            
            #wrapper #sidebar #top .heading#followontumblr {
                background-image: none;
                text-indent: 0;
            }
        
            #wrapper #sidebar #top .heading#twitter {
                background-image: none;
            }
        
            #wrapper #sidebar #top .heading#following {
                background-image: none;
            }

            #wrapper #content .post .audio .player {
                float: none;
            }
            
            #wrapper #content .post .audio .meta {
                display: none;
                float: none;
            }
        </style>
    <![endif]-->
    
    <!--[if lt IE 8.]>
        <style type="text/css">
            #wrapper #content .bottom {
                background: transparent;
            }
            
            #wrapper #content .post .footer {
                background: transparent;
                color: #000;
            }
            
            #wrapper #content .post .audio {
                float: none;
                background: transparent;
            }
            
            #wrapper #content .post .notecontainer .notes {
                padding: 0;
                margin: 0;
            }
        </style>
    <![endif]-->
    <style type="text/css">{CustomCSS}</style>
       <script>
    $(function() {
        $( "#accordion" ).accordion({
            collapsible: true,
            heightStyle: "content"
        });
    });
    </script>
</head>
<body>
    <div id="wrapper">
        <div id="title">
            </a>
        </div>
        
        <div id="content">
            
            {block:SearchPage}
                <div id="searchresults" class="searchresultcount">{SearchResultCount} results for <strong>"{SearchQuery}"</strong></div>
            {/block:SearchPage}
            
            {block:NoSearchResults}
                <style type="text/css">
                    .searchresultcount {
                        display: none;
                    }
                </style>
                <div id="searchresults">No results for <strong>"{SearchQuery}"</strong></div>
            {/block:NoSearchResults}
            
            {block:Posts}            
                <div class="post">
                    
                    {block:Photo}
                        <div class="media">{LinkOpenTag}<img src="{PhotoURL-500}" alt="{PhotoAlt}" />{LinkCloseTag}</div>
                        {block:Caption}<div class="copy">{Caption}</div>{/block:Caption}
                    {/block:Photo}
                    
                    {block:Video}
                        <div class="media">{Video-500}</div>
                        {block:Caption}<div class="copy">{Caption}</div>{/block:Caption}
                    {/block:Video}
                    
                    {block:Audio}
                        {block:IfShowAlbumArtOnAudioPosts}
                            {block:AlbumArt}
                                <div class="album_art">
                                    <img src="{AlbumArtURL}" alt="{block:Artist}{Artist}{/block:Artist}{block:TrackName} - {TrackName}{/block:TrackName}" style="margin-bottom: 10px" />
                                </div>
                            {/block:AlbumArt}
                        {/block:IfShowAlbumArtOnAudioPosts}
                        
                        <div class="audio">
                            <div class="player">{AudioPlayerWhite}</div>
                            <div class="meta">{PlayCountWithLabel}{block:ExternalAudio}<span class="download_external_audio"> &bull; <a href="{ExternalAudioURL}">download</a></span>{/block:ExternalAudio}</div>
                            <div class="clear"></div>
                        </div>
                        <div class="clear"></div>
                        {block:Caption}<div class="copy">{Caption}</div>{/block:Caption}
                    {/block:Audio}
                    
                    {block:Quote}
                        <div class="quote {Length}">{Quote}</div>
                        <div class="copy">
                            <div class="quotebg">“</div>
                            {block:Source}
                                <table border="0" cellpadding="0" cellspacing="0" width="100%">
                                    <tr>
                                        <td valign="top" style="width: 20px">&mdash;</td>
                                        <td valign="top" class="quote_source">
                                            {Source}
                                        </td>
                                    </tr>
                                </table>
                            {/block:Source}
                        </div>
                    {/block:Quote}
                        
                    {block:Text}
                        {block:Title}<div class="title">{Title}</div>{/block:Title}
                        <div class="copy">{Body}</div>
                    {/block:Text}
                    
                    {block:Answer}
                        <div class="question">
                            <div class="nipple"></div>
                            {Question}
                        </div>
                        <div class="asker_container"><img src="{AskerPortraitURL-24}">{Asker}</div>
                        <div class="copy">{Answer}</div>
                    {block:Answer}
                    
                    {block:Chat}
                        {block:Title}<div class="title">{Title}</div>{/block:Title}
                        <div class="chat">
                            <div class="lines">
                                {block:Lines}
                                    <div class="line {Alt}">{block:Label}<strong>{Label}</strong>{/block:Label} {Line}</div>
                                {/block:Lines}
                            </div>
                        </div>
                        <div class="clear"></div>
                        <div style="height: 10px"></div>
                    {/block:Chat}
                    
                    {block:Link}
                        <div class="link"><a href="{URL}" {Target}>{Name} &raquo;</a></div>
                        {block:Description}<div class="copy">{Description}</div>{/block:Description}
                    {/block:Link}
                    
                    {block:Date}
                        <a href="{Permalink}">
                            <div class="footer">
                                <div class="date">
                                    {block:Reblog}Reblogged{/block:Reblog}
                                    {block:NotReblog}Posted{/block:NotReblog}
                                    
                                    {TimeAgo}
                                    
                                    {block:Reblog}from {ReblogParentName} {block:RebloggedFromReblog}(originally from {ReblogRootName}){/block:RebloggedFromReblog}{/block:Reblog}
                                    {block:FromBookmarklet}from bookmarklet{/block:FromBookmarklet}
                                    {block:FromMobile}from mobile{/block:FromMobile}
                                </div>
                                <div class="notes">{block:NoteCount}{NoteCountWithLabel}{/block:NoteCount} {block:IfDisqusShortname}{block:NoteCount}&bull;{/block:NoteCount} <a href="{Permalink}#disqus_thread">view comments</a>{/block:IfDisqusShortname}</div>
                                <div class="clear"></div>
                            </div>
                        </a>
                    {/block:Date}
                    
                                        
                    {block:PostNotes}<div class="notecontainer">{PostNotes}</div>{/block:PostNotes}
                    
                    {block:IfDisqusShortname}
                        {block:Permalink}
                            <div class="notecontainer" style="margin: 20px 0 1px 0; padding: 1px 10px 10px 10px;">
                                <div id="disqus_thread"></div>
                                <script type="text/javascript" src="http://disqus.com/forums/{text:Disqus Shortname}/embed.js"></script>
                                <noscript><a href="http://{text:Disqus Shortname}.disqus.com/?url=ref">View the discussion thread.</a></noscript>
                            </div>
                            <div style="text-align: right; margin-top: 5px">
                                <a href="http://disqus.com" class="dsq-brlink">blog comments powered by <span class="logo-disqus">Disqus</span></a>
                            </div>
                        {/block:Permalink}
                    {/block:IfDisqusShortname}
                    
                </div>
                <div class="bottom"></div>
            {/block:Posts}
            
            {block:Pagination}
                <div id="navigation">
                    {block:PreviousPage}<a href="{PreviousPage}">&larr; previous page</a>{/block:PreviousPage}
                    {block:NextPage}<a href="{NextPage}">next page &rarr;</a>{/block:NextPage}
                </div>
            {/block:Pagination}
            
        </div>
        
        <div id="sidebar">
            <div id="top">
                <br>
<div id="description">{Description}</div>
                
                
                
                {block:HasPages}
                    <div id="pages">
                        {block:Pages}<a href="{URL}" class="page">{Label}</a>{/block:Pages}
                        <div class="clear"></div>
                    </div>
                {/block:HasPages}
                <div id="pages" class="ask_and_submit">
                    {block:AskEnabled}<a href="/ask" class="page">{AskLabel}</a>{/block:AskEnabled}
                    {block:SubmissionsEnabled}<a href="/submit" class="page">{SubmitLabel}</a>{/block:SubmissionsEnabled}
                    <div class="clear"></div>
                </div>
                
                <div id="search">
                
                
                <form method="get" name="searchform" action="http://www.google.com/search" target="_blank">
            <input type="hidden" name="sitesearch" value="www.richestzebra.com">
            <input onfocus="searchfield_focus(this)" onblur="searchfield_unfocus(this)" class="query" type="text" name="as_q" size="20" value="find old stuff...">
            <input type="submit" value="Search" title="Search" class="submit">
            </form>
<script>                
function searchfield_focus(obj)
{
obj.style.color=""
obj.style.fontStyle=""
if (obj.value=="find old stuff...")
    {obj.value=""}
}
function searchfield_unfocus(obj)
{
if (obj.value=="")
    {obj.value="find old stuff..."}
}

</script>
<div class="clear"></div>
                </div>
              
                             
               
                
                {block:IfShowPeopleIFollow}
                    {block:Following}
                        <div class="heading" id="following">Following</div>
                        <div class="content" id="following-avatars">
                            {block:Followed}<a href="{FollowedURL}"><img src="{FollowedPortraitURL-40}" /></a>{/block:Followed}
                        </div>
                    {/block:Following}
                {/block:IfShowPeopleIFollow}
                
                <div id="buttons">
                    <div class="row">
                        <div class="button" id="button-rss"><a href="{RSS}">RSS Feed</a></div>
                        <div class="button" id="button-random"><a href="/random">Random</a></div>
                    </div>
                    <div class="clear"></div>
                    <div class="row">
                        <div class="button" id="button-archive"><a href="/archive">Archive</a></div>
                        <div class="button" id="button-mobile"><a href="/mobile">Mobile</a></div>
                    </div>
                    <div class="clear"></div>
                </div>
                
            </div>
            
            <div id="bottom"></div>
            <div id="copyright">&copy; {CopyrightYears} </div>
        </div>
        
        <div class="clear"></div>
    </div>
    
    {block:Twitter}
        <script type="text/javascript">
            var recent_tweets;
            function recent_tweets(x){
                try{recent_tweets = JSON.parse(x)}
                catch(e){console.log('...well that didn\'t work')}
                
            }
        </script>
        <script type="text/javascript" src="/tweets.js"></script>
    {/block:Twitter}
    
    {block:IfDisqusShortname}
        <script type="text/javascript">
            //<![CDATA[
            (function() {
                var links = document.getElementsByTagName('a');
                var query = '?';
                for(var i = 0; i < links.length; i++) {
                    if(links[i].href.indexOf('#disqus_thread') >= 0) {
                        query += 'url' + i + '=' + encodeURIComponent(links[i].href) + '&';
                    }
                }
                document.write('<script charset="utf-8" type="text/javascript" src="http://disqus.com/forums/{text:Disqus Shortname}/get_num_replies.js' + query + '"></' + 'script>');
            })();
            //]]>
        </script>
    {/block:IfDisqusShortname}
</body>
</html>
```

### Appearence Options  

**Title:** Richest Zebra  

```
<DIV ALIGN=CENTER>
<p style="text-align:center;">
<b>RichestZebra.com</b></p>
<p style="text-align:center; margin-top:-20px;"><br>moderately entertaining stuff...<br>often posted sporadically</p>

<a href="http://www.facebook.com/brice.shatzer"> <i class="fa fa-facebook-square" style="font-size:4.2em"></i>
</a>&nbsp;
<a href="http://www.linkedin.com/pub/brice-shatzer/16/690/b26">
<i class="fa fa-linkedin-square" style="font-size:4.2em"></i>
</a>&nbsp;
<a href="mailto:brice.shatzer@gmail.com">
<i class="fa fa-envelope-square" style="font-size:4.2em"></i>
</a>&nbsp;<a href="https://www.youtube.com/user/shatzofhudson/videos" target="_blank">
<i class="fa fa-youtube-square" style="font-size:4.2em"></i></a>
 </div>
 
 
<script type="text/javascript">

  var _gaq = _gaq || [];
  _gaq.push(['_setAccount', 'UA-16891970-1']);
  _gaq.push(['_trackPageview']);

  (function() {
    var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
    ga.src = ('https:' == document.location.protocol ? 'https://' : 'http://') + 'stats.g.doubleclick.net/dc.js';    
    var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
  })();

</script>
<style>#following,#following-avatars{display:none;}
#wrapper #sidebar #bottom{
background-color:#fff;
border-bottom-left-radius:10px;
border-bottom-right-radius:10px;
}
</style>
```  

### Theme Options:  

- Background Color: `#000000`  
- Title: Arial  
- Body: Arial  
- Accent: Lucida Sans


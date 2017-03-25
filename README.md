<Title>my name is raju</Title>
<!DOCTYPE html>
<!--
 *  Copyright (c) 2015 The WebRTC project authors. All Rights Reserved.
 *
 *  Use of this source code is governed by a BSD-style license
 *  that can be found in the LICENSE file in the root of the source
 *  tree.
-->
<html>
<head>

  <meta charset="utf-8">
  <meta name="description" content="WebRTC code samples">
  <meta name="viewport" content="width=device-width, user-scalable=yes, initial-scale=1, maximum-scale=1">
  <meta itemprop="description" content="Client-side WebRTC code samples">
  <meta itemprop="image" content="../../../images/webrtc-icon-192x192.png">
  <meta itemprop="name" content="WebRTC code samples">
  <meta name="mobile-web-app-capable" content="yes">
  <meta id="theme-color" name="theme-color" content="#ffffff">

  <base target="_blank">

  <title>getUserMedia</title>

  <link rel="icon" sizes="192x192" href="../../../images/webrtc-icon-192x192.png">
  <link href="//fonts.googleapis.com/css?family=Roboto:300,400,500,700" rel="stylesheet" type="text/css">
  <link rel="stylesheet" href="../../../css/main.css">

</head>

<body>

  <div id="container">

    <div class="highlight">
      <p>New codelab: <a href="https://codelabs.developers.google.com/codelabs/webrtc-web">Realtime communication with WebRTC</a></p>
    </div>

    <h1><a href="//webrtc.github.io/samples/" title="WebRTC samples homepage">WebRTC samples</a> <span>getUserMedia</span></h1>

    <video id="gum-local" autoplay></video>

    <div id="errorMsg"></div>

    <p class="warning"><strong>Warning:</strong> if you're not using headphones, pressing play will cause feedback.</p>

    <p>Display the video stream from <code>getUserMedia()</code> in a video element.</p>

    <p>The <code>MediaStream</code> object <code>stream</code> passed to the <code>getUserMedia()</code> callback is in global scope, so you can inspect it from the console.</p>

    <a href="https://github.com/webrtc/samples/tree/gh-pages/src/content/getusermedia/gum" title="View source for this page on GitHub" id="viewSource">View source on GitHub</a>
  </div>

  <script src="https://webrtc.github.io/adapter/adapter-latest.js"></script>
  <script src="../../../js/common.js"></script>
  <script src="js/main.js"></script>

  <script src="../../../js/lib/ga.js"></script>

</body>
</html>

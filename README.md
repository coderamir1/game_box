//کد آموزش اول
wv.setWebViewClient(new WebViewClient()); 
wv.getSettings().setLoadWithOverviewMode(true);
wv.getSettings().setUseWideViewPort(true);
wv.getSettings().setJavaScriptEnabled(true);
wv.getSettings().setPluginState(WebSettings.PluginState.ON);
wv.getSettings().setAllowFileAccess(true);
wv.getSettings().setAllowContentAccess(true);
wv.getSettings().setAllowFileAccessFromFileURLs(true);
wv.getSettings().setAllowUniversalAccessFromFileURLs(true);

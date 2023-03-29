# allo
5. Разворачиваем тестовое приложение  cd $HOME mkdir demo_deploy_Leo_app &amp;&amp; cd demo_deploy_Leo_app Далее вставляем адрес вашего кошелька  WALLETADDRESS="" APPNAME=helloworld_"${WALLETADDRESS:4:6}" echo $APPNAME leo new "${APPNAME}" cd "${APPNAME}" &amp;&amp; leo run &amp;&amp; cd -

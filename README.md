<!DOCTYPE html>
<head>    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.5.1/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.5.1/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://rawcdn.githack.com/python-visualization/folium/master/folium/templates/leaflet.awesome.rotate.css"/>
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_23bff1b965324a86869c10f392d39839 {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
            </style>
        
</head>
<body>    
    
            <div class="folium-map" id="map_23bff1b965324a86869c10f392d39839" ></div>
        
</body>
<script>    
    
            var map_23bff1b965324a86869c10f392d39839 = L.map(
                "map_23bff1b965324a86869c10f392d39839",
                {
                    center: [14.589896, 120.982292],
                    crs: L.CRS.EPSG3857,
                    zoom: 12,
                    zoomControl: true,
                    preferCanvas: false,
                }
            );

            

        
    
            var tile_layer_18c53971fc50450c8a04bc76db725ee9 = L.tileLayer(
                "https://stamen-tiles-{s}.a.ssl.fastly.net/terrain/{z}/{x}/{y}.jpg",
                {"attribution": "Map tiles by \u003ca href=\"http://stamen.com\"\u003eStamen Design\u003c/a\u003e, under \u003ca href=\"http://creativecommons.org/licenses/by/3.0\"\u003eCC BY 3.0\u003c/a\u003e. Data by \u0026copy; \u003ca href=\"http://openstreetmap.org\"\u003eOpenStreetMap\u003c/a\u003e, under \u003ca href=\"http://creativecommons.org/licenses/by-sa/3.0\"\u003eCC BY SA\u003c/a\u003e.", "detectRetina": false, "maxNativeZoom": 18, "maxZoom": 18, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            ).addTo(map_23bff1b965324a86869c10f392d39839);
        
    
            var marker_36ce7bf3c0144034b2753009a5d3c1de = L.marker(
                [14.5929, 120.9733],
                {}
            ).addTo(map_23bff1b965324a86869c10f392d39839);
        
    
            var icon_95374cd892dc43b9b7416742522be106 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_36ce7bf3c0144034b2753009a5d3c1de.setIcon(icon_95374cd892dc43b9b7416742522be106);
        
    
        var popup_69190a8a70754a0082f3720e1c145f76 = L.popup({"maxWidth": "100%"});

        
            var html_8fa3fd82c25c4e17bae0fe4eff47a1e2 = $(`<div id="html_8fa3fd82c25c4e17bae0fe4eff47a1e2" style="width: 100.0%; height: 100.0%;"><strong>Intramuros Branch</strong><br>Open time: 9 A.M. - 4 P.M.</br> [14.5929,120.9733]</div>`)[0];
            popup_69190a8a70754a0082f3720e1c145f76.setContent(html_8fa3fd82c25c4e17bae0fe4eff47a1e2);
        

        marker_36ce7bf3c0144034b2753009a5d3c1de.bindPopup(popup_69190a8a70754a0082f3720e1c145f76)
        ;

        
    
    
            marker_36ce7bf3c0144034b2753009a5d3c1de.bindTooltip(
                `<div>
                     Intramuros Branch
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c71072b0f7d84fe88e5b3b456267d0ef = L.marker(
                [14.6126, 120.9936],
                {}
            ).addTo(map_23bff1b965324a86869c10f392d39839);
        
    
            var icon_78adec73568749cfa9507acfce96faad = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_c71072b0f7d84fe88e5b3b456267d0ef.setIcon(icon_78adec73568749cfa9507acfce96faad);
        
    
        var popup_30a6b02614914285a5f6a8f6518d338f = L.popup({"maxWidth": "100%"});

        
            var html_fcf0b1cff8ca40038516b742557f1623 = $(`<div id="html_fcf0b1cff8ca40038516b742557f1623" style="width: 100.0%; height: 100.0%;"><strong>Sampaloc Branch</strong><br>Open time: 9 A.M. - 4 P.M.</br> [14.6126,120.9936]</div>`)[0];
            popup_30a6b02614914285a5f6a8f6518d338f.setContent(html_fcf0b1cff8ca40038516b742557f1623);
        

        marker_c71072b0f7d84fe88e5b3b456267d0ef.bindPopup(popup_30a6b02614914285a5f6a8f6518d338f)
        ;

        
    
    
            marker_c71072b0f7d84fe88e5b3b456267d0ef.bindTooltip(
                `<div>
                     Sampaloc Branch
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_cafa55908f674cbfb71cd4329919662e = L.marker(
                [14.598, 121.018],
                {}
            ).addTo(map_23bff1b965324a86869c10f392d39839);
        
    
            var icon_e04bae0b633c41e49d21b395f46207f0 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_cafa55908f674cbfb71cd4329919662e.setIcon(icon_e04bae0b633c41e49d21b395f46207f0);
        
    
        var popup_77f417ba2f744427af5fe78ed96a5261 = L.popup({"maxWidth": "100%"});

        
            var html_8d7da75e7b5746628abc7b80f798aae4 = $(`<div id="html_8d7da75e7b5746628abc7b80f798aae4" style="width: 100.0%; height: 100.0%;"><strong>Sampaloc - Old Santa Mesa Branch</strong><br>Open time: 9 A.M. - 4 P.M.</br> [14.598,121.018]</div>`)[0];
            popup_77f417ba2f744427af5fe78ed96a5261.setContent(html_8d7da75e7b5746628abc7b80f798aae4);
        

        marker_cafa55908f674cbfb71cd4329919662e.bindPopup(popup_77f417ba2f744427af5fe78ed96a5261)
        ;

        
    
    
            marker_cafa55908f674cbfb71cd4329919662e.bindTooltip(
                `<div>
                     Sampaloc - Old Santa Mesa Branch
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_da147607368b4977ab11372128630159 = L.marker(
                [14.5693, 120.9867],
                {}
            ).addTo(map_23bff1b965324a86869c10f392d39839);
        
    
            var icon_fa14db1dc5cd49f8bd50128ae47773c1 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_da147607368b4977ab11372128630159.setIcon(icon_fa14db1dc5cd49f8bd50128ae47773c1);
        
    
        var popup_5f36740aec27476888b28a1b2b91a6a2 = L.popup({"maxWidth": "100%"});

        
            var html_d095d967a2684b67bfa2db966a0824f2 = $(`<div id="html_d095d967a2684b67bfa2db966a0824f2" style="width: 100.0%; height: 100.0%;"><strong>Malate  Branch</strong><br>Open time: 9 A.M. - 4 P.M.</br> [14.5693,120.9867]</div>`)[0];
            popup_5f36740aec27476888b28a1b2b91a6a2.setContent(html_d095d967a2684b67bfa2db966a0824f2);
        

        marker_da147607368b4977ab11372128630159.bindPopup(popup_5f36740aec27476888b28a1b2b91a6a2)
        ;

        
    
    
            marker_da147607368b4977ab11372128630159.bindTooltip(
                `<div>
                     Malate  Branch
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_140a4827ae984bd9a31238107c87f7ef = L.marker(
                [14.5807, 120.9807],
                {}
            ).addTo(map_23bff1b965324a86869c10f392d39839);
        
    
            var icon_7a3a0af9db2b4e70a104e10cf9d03516 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_140a4827ae984bd9a31238107c87f7ef.setIcon(icon_7a3a0af9db2b4e70a104e10cf9d03516);
        
    
        var popup_55f72fc0fcba4e508675dd4b2cbbae67 = L.popup({"maxWidth": "100%"});

        
            var html_e5fa6458cfdc4f8687050291e7abcfdc = $(`<div id="html_e5fa6458cfdc4f8687050291e7abcfdc" style="width: 100.0%; height: 100.0%;"><strong>Ermita Branch</strong><br>Open time: 9 A.M. - 4 P.M.</br> [14.5807,120.9807]</div>`)[0];
            popup_55f72fc0fcba4e508675dd4b2cbbae67.setContent(html_e5fa6458cfdc4f8687050291e7abcfdc);
        

        marker_140a4827ae984bd9a31238107c87f7ef.bindPopup(popup_55f72fc0fcba4e508675dd4b2cbbae67)
        ;

        
    
    
            marker_140a4827ae984bd9a31238107c87f7ef.bindTooltip(
                `<div>
                     Ermita Branch
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_d8fa937971f44ccaa7f7b6f81b6b337d = L.marker(
                [14.6224, 120.972],
                {}
            ).addTo(map_23bff1b965324a86869c10f392d39839);
        
    
            var icon_b045b93af9e64d4ca487758bb819d638 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_d8fa937971f44ccaa7f7b6f81b6b337d.setIcon(icon_b045b93af9e64d4ca487758bb819d638);
        
    
        var popup_744e6cc9bc3c457cb5339432f5c322d5 = L.popup({"maxWidth": "100%"});

        
            var html_b65d70cb06ea4479bf1157551b6485f9 = $(`<div id="html_b65d70cb06ea4479bf1157551b6485f9" style="width: 100.0%; height: 100.0%;"><strong>Tondo  Branch</strong><br>Open time: 9 A.M. - 4 P.M.</br> [14.6224,120.972]</div>`)[0];
            popup_744e6cc9bc3c457cb5339432f5c322d5.setContent(html_b65d70cb06ea4479bf1157551b6485f9);
        

        marker_d8fa937971f44ccaa7f7b6f81b6b337d.bindPopup(popup_744e6cc9bc3c457cb5339432f5c322d5)
        ;

        
    
    
            marker_d8fa937971f44ccaa7f7b6f81b6b337d.bindTooltip(
                `<div>
                     Tondo  Branch
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_67dbd5a2380f477e846c331a86f36f34 = L.marker(
                [14.5994, 120.9835],
                {}
            ).addTo(map_23bff1b965324a86869c10f392d39839);
        
    
            var icon_1dcae262d2084f5a8d85632f34d7affa = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_67dbd5a2380f477e846c331a86f36f34.setIcon(icon_1dcae262d2084f5a8d85632f34d7affa);
        
    
        var popup_133a70db124a49d4a28c2a4d3251e809 = L.popup({"maxWidth": "100%"});

        
            var html_dbafde7afcea49f69cb9165f65a21c82 = $(`<div id="html_dbafde7afcea49f69cb9165f65a21c82" style="width: 100.0%; height: 100.0%;"><strong>Sta. Cruz- Quiapo  Branch</strong><br>Open time: 9 A.M. - 4 P.M.</br> [14.5994,120.9835]</div>`)[0];
            popup_133a70db124a49d4a28c2a4d3251e809.setContent(html_dbafde7afcea49f69cb9165f65a21c82);
        

        marker_67dbd5a2380f477e846c331a86f36f34.bindPopup(popup_133a70db124a49d4a28c2a4d3251e809)
        ;

        
    
    
            marker_67dbd5a2380f477e846c331a86f36f34.bindTooltip(
                `<div>
                     Sta. Cruz- Quiapo  Branch
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_84cea65b95fc4c328d42c1d32d8e7a9e = L.marker(
                [14.6064, 120.9682],
                {}
            ).addTo(map_23bff1b965324a86869c10f392d39839);
        
    
            var icon_57be7561ba3b41da8d91f1b20a979dce = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_84cea65b95fc4c328d42c1d32d8e7a9e.setIcon(icon_57be7561ba3b41da8d91f1b20a979dce);
        
    
        var popup_8eed97e24a0445278b463e74c5519eb9 = L.popup({"maxWidth": "100%"});

        
            var html_c4db10ce966842bfaae9309b12dcfa9e = $(`<div id="html_c4db10ce966842bfaae9309b12dcfa9e" style="width: 100.0%; height: 100.0%;"><strong>Binondo  - San Nicolas Branch</strong><br>Open time: 9 A.M. - 4 P.M.</br> [14.6064,120.9682]</div>`)[0];
            popup_8eed97e24a0445278b463e74c5519eb9.setContent(html_c4db10ce966842bfaae9309b12dcfa9e);
        

        marker_84cea65b95fc4c328d42c1d32d8e7a9e.bindPopup(popup_8eed97e24a0445278b463e74c5519eb9)
        ;

        
    
    
            marker_84cea65b95fc4c328d42c1d32d8e7a9e.bindTooltip(
                `<div>
                     Binondo  - San Nicolas Branch
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_a2adeace466043c5bf3cb2446692ea25 = L.marker(
                [14.5916, 121.0055],
                {}
            ).addTo(map_23bff1b965324a86869c10f392d39839);
        
    
            var icon_cba8dfb11db84371a0fb82b70207c423 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_a2adeace466043c5bf3cb2446692ea25.setIcon(icon_cba8dfb11db84371a0fb82b70207c423);
        
    
        var popup_c286360989ed4e4ea1e61fa76ca27a36 = L.popup({"maxWidth": "100%"});

        
            var html_68d98a7652aa4396b44f21780ea1d629 = $(`<div id="html_68d98a7652aa4396b44f21780ea1d629" style="width: 100.0%; height: 100.0%;"><strong>Pandacan - Sta. Ana Branch</strong><br>Open time: 9 A.M. - 4 P.M.</br> [14.5916,121.0055]</div>`)[0];
            popup_c286360989ed4e4ea1e61fa76ca27a36.setContent(html_68d98a7652aa4396b44f21780ea1d629);
        

        marker_a2adeace466043c5bf3cb2446692ea25.bindPopup(popup_c286360989ed4e4ea1e61fa76ca27a36)
        ;

        
    
    
            marker_a2adeace466043c5bf3cb2446692ea25.bindTooltip(
                `<div>
                     Pandacan - Sta. Ana Branch
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_c71726e5306e4d56b5b9be17bffb755c = L.marker(
                [14.5773, 120.9908],
                {}
            ).addTo(map_23bff1b965324a86869c10f392d39839);
        
    
            var icon_317556b3fd304084a937dcf84ce263ad = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_c71726e5306e4d56b5b9be17bffb755c.setIcon(icon_317556b3fd304084a937dcf84ce263ad);
        
    
        var popup_fa1ec90133ed40a781ba8613fd1843f4 = L.popup({"maxWidth": "100%"});

        
            var html_f5d983144c04487dbf2a203bcd38346d = $(`<div id="html_f5d983144c04487dbf2a203bcd38346d" style="width: 100.0%; height: 100.0%;"><strong>Paco - San Andres  Branch</strong><br>Open time: 9 A.M. - 4 P.M.</br> [14.5773,120.9908]</div>`)[0];
            popup_fa1ec90133ed40a781ba8613fd1843f4.setContent(html_f5d983144c04487dbf2a203bcd38346d);
        

        marker_c71726e5306e4d56b5b9be17bffb755c.bindPopup(popup_fa1ec90133ed40a781ba8613fd1843f4)
        ;

        
    
    
            marker_c71726e5306e4d56b5b9be17bffb755c.bindTooltip(
                `<div>
                     Paco - San Andres  Branch
                 </div>`,
                {"sticky": true}
            );
        
</script>

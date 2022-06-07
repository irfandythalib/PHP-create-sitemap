<?php
$xmlString = '<?xml version="1.0" encoding="UTF-8"?>
    <urlset 
	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
	xmlns:image="http://www.google.com/schemas/sitemap-image/1.1" 
	xsi:schemaLocation="http://www.sitemaps.org/schemas/sitemap/0.9 http://www.sitemaps.org/schemas/sitemap/0.9/sitemap.xsd" 
	xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">';


//You can foreach this if you have an array list
	$xmlString .= '<url>
            <loc>https://your-url-here</loc>
            <changefreq>weekly/monthly</changefreq>
			<priority>0.8</priority>
        </url>';

        
$xmlString .= '</urlset>';

$dom = new DOMDocument;
$dom->preserveWhiteSpace = FALSE;
$dom->loadXML($xmlString);

//Save XML as a file
$dom->save('your-xml-file.xml');
?>

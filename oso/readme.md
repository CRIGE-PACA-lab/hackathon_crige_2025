# Utiliser un raster compressé (format cog.tif) sous Qgis  

## Généralités 

Le format Cloud Optimized GeoTIFF (COG) est un type de raster GeoTIFF spécialement conçu pour la diffusion web. 
Il est plus léger que le Geotiff classique et n'a **pas besoin d'être téléchargé** pour être exploité. 
Toutefois, en cas de mauvaise connexion, il peut tout à fait être téléchargé et charger en local comme un raster classique

## Mode d'emploi

### 1) Récupérer le lien du raster sous Github 

Par exemple, pour récupéré un MNT départemental à 5 mètres de résolution : 

	1. Entrer dans le dossier contenant sur le raster (.../rge_alti_5m) 
	2. Cliquer sur le raster souhaité (.../rge_alti_5m/rge_alti_5m_04_ass_cog.tif)
	3. Clic droit sur "View raw" : "copier le lien" (clique gauche pour télécharger)

![image_viewraw](images/image_720.png)

### 2) Sous Qgis 

	1. Ouvrir Qgis 
	2. Couche 
	3. Ajouter une couche 
	4. Ajouter une couche raster 
	5. Type de source : selectionner "Protocole : HTTP(S),cloud, etc."
	6. Coller le lien du raster 
	7. Cliquer sur ajouter
	
![image_viewraw](images/image_721.png)

![image_viewraw](images/image_722.png)

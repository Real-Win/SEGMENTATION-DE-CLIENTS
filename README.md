# Segmentation de clients avec K-Means

Clustering non supervisé sur le dataset Mall Customers (200 clients).

## Résultats
5 segments trouvés avec K-Means (silhouette = 0,55 à k=5) sur le revenu et le score de dépense.

## Leçon principale
Une colonne d'identifiant (CustomerID) dans les données produisait de faux groupes. La retirer a fait apparaître des profils lisibles.

## Limites
200 clients seulement, score de dépense défini par le centre commercial, photo à un seul moment.

## Lancer le projet
pip install -r requirements.txt
Puis ouvrir segmentation_clients.ipynb

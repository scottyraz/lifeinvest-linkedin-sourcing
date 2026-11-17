# Schema de sortie Google Sheets
Colonnes souhaitees (ne pas imposer une reorganisation destructive a un classeur existant):
ID_Lead | Nom | Prenom | LinkedIn_URL | Entreprise | Fonction | Secteur | Pays | Ville | Annees_experience_verifiees | Source_experience | Preuve_francophone | Source_langue | Signal_public_personnalise | Source_signal | Source_entreprise | Score_LifeInvest_5 | Justification_score | Type_prospect | Angle_approche | Message_LinkedIn | Statut | Points_a_verifier | Date_verification | Source_recherche.

Valeurs de statut initial: `Preselection - non contacte`; `A revalider - non contacte`; `Exclu`. Type_prospect: `Investisseur potentiel`, `Partenaire`, `A qualifier`. Le score n'est pas une qualification financiere. Une donnee absente doit etre `Non verifie`, pas une valeur inventee. Ajouter les colonnes uniquement avec autorisation explicite de modifier la structure du classeur.

Rapport de livraison: zone, date, quota, nombre examines, retenus, exclus, doublons, 5 meilleurs avec URL et justification, liste des lacunes, confirmation `Aucun message envoye` si verifiable.

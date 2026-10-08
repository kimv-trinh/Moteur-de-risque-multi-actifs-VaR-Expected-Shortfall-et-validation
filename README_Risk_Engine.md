# Moteur de risque multi-actifs (VaR / Expected Shortfall)

Notebook de mesure du risque de marché d'un portefeuille multi-actifs. Il estime la VaR et l'Expected Shortfall par trois méthodes (paramétrique, historique, Monte-Carlo), décompose le risque par actif, valide le modèle par backtesting (Kupiec, Christoffersen), le rend conditionnel (EWMA, GARCH-FHS) et le soumet à des scénarios de stress.

## Dépendances

```bash
pip install numpy pandas scipy matplotlib yfinance arch
```

## Utilisation

Ouvrir `Risk_Engine.ipynb` dans Jupyter et exécuter les cellules dans l'ordre. Les données de marché sont téléchargées automatiquement via yfinance (aucune clé API requise).

## Contenu

Le notebook est organisé en 14 parties numérotées, de la collecte des données au scorecard comparatif des modèles, chacune autonome et commentée.

Réalisé par Kim TRINH.

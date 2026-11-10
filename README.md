# CentralPilote

Supervision multi-sites : commandes, alertes, stock et finances de tous les points de vente sur une seule carte.

- Front : `index.html` (statique, déployé sur Vercel)
- Back : Supabase (projet `centralpilote`, eu-west-3) — tables avec RLS, RPC `cp_place_order` / `cp_adj_stock`, Edge Function `cp-account`

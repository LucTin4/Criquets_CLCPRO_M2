
digraph G {

/*Acteurs*/
"Etat Mauritanien" [color = green]
"CLCPRO"[color = green]
"Bailleurs internationaux"[color = green]
"Chercheurs"[color = green]
"CNLAA" [color = green]
"Directeur CNLAA"[color = green]
"Prospecteurs expérimentés"[color = green]
"Prospecteurs débutants"[color = green]
"Eleveurs nomades"[color = green]
"Cultivateurs"[color = green]
"Autorités locales"[color = green]
"Criquets solitaires"[color = green]
"Criquets grégaires"[color = green]
"Animaux"[color = green]
/*ressources*/
"Vegetation"[color = blue]
"Insecticides"[color = blue]
"Conflits"[color = blue]
"Fiche e-locust"[color = blue]
"Points d'eau"[color = blue]
/*interactions*/
"Etat Mauritanien"->"CNLAA"[label="finance"]
"Bailleurs internationaux"->"Chercheurs"[label="finance"]
"Bailleurs internationaux"->"CLCPRO"[label="finance"]
"CNLAA"->"Prospecteurs expérimentés"[label="emploie"]
"CNLAA"->"Prospecteurs débutants"[label="emploie"]
"Eleveurs nomades"->"Criquets solitaires"[label="surveillent"]
"Cultivateurs"->"Criquets solitaires"[label="surveillent"]
"Autorités locales"->"Criquets solitaires"[label="surveillent"]
"Criquets solitaires"->"Criquets grégaires"[label="deviennent"]
"Vegetation"-> "Criquets grégaires"[label="favorise"]
"Animaux"->"Criquets grégaires"[label="signalent"]
"Conflits"->"Criquets grégaires"[label="favorisent"]
"Conflits"->"Prospecteurs expérimentés"[label="bloquent"]
"Conflits"->"Prospecteurs débutants"[label="bloquent"]
"Prospecteurs expérimentés"->"Prospecteurs débutants"[label="forment"]
"Prospecteurs expérimentés"->"Fiche e-locust"[label="renseignent"]
"Prospecteurs débutants"->"Fiche e-locust"[label="renseignent partiellement"]
"Prospecteurs expérimentés"->"Insecticides"[label="utilisent"]
"Prospecteurs expérimentés"->"Eleveurs nomades"[label="échangent"]
"Insecticides"->"Criquets grégaires"[label="tuent"]
"Insecticides"->"Points d'eau"[label="polluent"]
"Insecticides"->"Vegetation"[label="polluent"]

}
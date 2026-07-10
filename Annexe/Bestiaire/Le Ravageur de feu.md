```statblock
image: [[Ravageur.png]]
name: Le Ravageur de feu
size: G
type: Fiélon
subtype: 
alignment: Loyal Mauvais
ac: 16 (armure naturelle)
hp: 112
hit_dice: 15d10+30
speed: 12 m
stats: [18, 14, 15, 11, 10, 12]
saves:
  - Intelligence: +3
  - Sagesse: +3
  - Charisme: +4
skillsaves:
  - Perspicacité: +3
  - Supercherie: +4
damage_resistances: contondants, perforants et tranchants inflgiés par des attaques non-magiques qui ne sont pas magiques
damage_immunities: de feu
condition_immunities: [[Empoisonné]]
damage_vulnerabilities: de froid
senses: vision dans le noir 18 m, Perception passive 10
languages: commun, ignée, gnome, télépathie 36 m
cr: 7
traits:
  - name: Armes surchauffées
    desc: "Quand le ravageur réussit une attaque avec une arme de corps-à-corps en métal, celle-ci inflige 3 (1d6) dégâts de feu supplémentaires (inclus dans l’attaque)."
  - name: Corps surchauffé
    desc: "Une créature qui touche le ravageur ou qui réussit une attaque au corps-à-corps contre lui à une distance maximale de 1,50 mètre subit 7 (2d6) dégâts de feu."
  - name: Repli (Recharge 6)
    desc: "Le ravageur peut utiliser sa réaction afin de se téléporter sur 36 m."
  - name: Pouvoirs du ravageur
    desc: "Le ravageur peut utiliser les sorts suivant à leur niveau minimal : [[Soin des blessures]], [[Blessure]], [[Détection du mal et du bien]], [[Détection de la magie]], [[Détection des pensées]], [[Voir l'invisible]], [[Compréhension des langues]]. Il peut lancer chacun de ces sorts une fois entre chaque repos court ou long."
  - name: Insondable
    desc: "Le ravageur est en permanence sous l’effet du sort esprit impénétrable. Cet effet ne peut être détecté avec le sort détection de la magie."
actions:
  - name: Attaques multiples
    desc: "Le ravageur effectue deux attaques : une avec sa lance et une avec sa queue."
  - name: Lance
    desc: "Attaque d’arme au corps-à-corps ou à distance : +8 pour toucher, allonge 1,50 m ou portée 6/18 m, une cible. Touché : 12 (2d6+5) dégâts perforants ou 14 (2d8+5) dégâts perforants si elle est maniée à deux mains pour effectuer une attaque au corps-à-corps, + 3 (1d6) dégâts de feu."
  - name: Queue
    desc: "Attaque d’arme au corps-à-corps : +7 pour toucher, allonge 3 m, une cible. Touché : 11 (2d6+4) dégâts contondants + 7 (2d6) dégâts de feu et la cible est empoignée (jet de sauvegarde de Dextérité DD14 en H&D, ou de Dextérité DD12 en CO). Jusqu’à la fin de cette empoignade, la cible est entravée et le ravageur peut réussir automatiquement une attaque de queue contre elle, mais ne peut plus effectuer d’attaque de queue contre d’autres cibles.."
```

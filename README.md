
# RUBY-INTRO-TEST-THP

<a href="https://www.thehackingproject.org/">
    <img src="https://www.thehackingproject.org/packs/media/images/logo/20210910-THP-Logo_color_transparent-7bcda2eebdfc9e089cfe84bda563a4e7.png" style="height:100px">
</a>
<br/>

Une série de tests portée sur ruby en 3 catégories de difficultés. Ces tests vous permettront de voir les acquis que vous avez engrangé durant c'est deux semaines de ruby.

## Partie "Base" :

1. **Question 1 (variable ruby)**
- Comment déclarer une variable ?

2. **Question 2 (type de variable)**
- Qu'elle est là différence entre `i = 2` et `i = "2"` ?

3. **Question 3 (addition)**
- Résoudre l'addition suivante :
```ruby
i = 5
a = 2
```
Combien font `i + 5 * a` ?

4. **Question 4 (incrémentation et décrémentation)**
- Qu'est-ce que l'incrémentation et la décrémentation
5. Dans les lignes suivante, lesquels fonctionnent ?
```ruby
1|   i = i + 1 // i = i - 1
2|   i++ // i--
3|   i+1 // i-1
4|   ++i // --i
5|   i.inc // i.dec
6|   i += 1 // i -= 1

```

6. **Question 5 (type de variable)**
- Qu'est-ce qu'un Array ?

7. **Question 6 (boucles)**
- Comment écrire une boucle `while`, `for` ou `each` ?

8. **Question 7 (conditionnelle)**
- Quelle est la syntaxe pour une structure conditionnelle "if, else if, else" en Ruby ?

9. **Question 8 (opérateurs logiques)**
- Expliquez les opérateurs logiques "&&", "||" et "!".

10. **Question 9 (index et tableau)**
- Dans mon tableau `my_tab` comment imprimer la première et la 3eme valeurs du tableau dans le terminal avec un index ?

11. **Question 10 (input utilisateur)**
- Comment obtenir une saisie terminal de l'utilisateur et l'affecter à une variable ?

12. **Question 11 (méthodes de conversion de types)**
- Quelles méthodes peut-on utiliser pour convertir un nombre en chaîne de caractères et vice versa en Ruby ?

13. **Question 12 (commentaires)**
- Comment ajouter un commentaire en Ruby ? À quoi servent les commentaires dans le code ?

14. **Question 13 (méthodes de classe)**
- Quelles sont les méthodes de classe pour manipuler les chaînes de caractères en Ruby, telles que :
la longueur d'une chaine ?
le type d'une variable ?
la variable est vide ?

15. **Question 14 (opérateurs de comparaison)**
- Expliquez les opérateurs de comparaison (==, !=, <, >, <=, >=).

16. **Question 15 (cas de saisie)**
- Comment gérer des cas précis suite à une saisie utilisateur ? (ex: o pour quitter; 1 pour afficher une liste; ...)

## Partie "Standard" :

1. **Question 1 (Manipulation d'array)**
- Dans un tableau d'entiers, comment trier les valeurs par ordre croissant ?
- Comment faire pour le trier par ordre décroissant ?

2. **Question 2 (Convention ruby)**
- Quelle convention typographique est utilisée dans la nomination des méthodes en ruby ?

3. **Question 3 (méthodes)**
- Dans les codes suivant, il y a des trous et des erreurs, lesquels ?

```ruby
def my_fonction(input_str)
    puts input_str
end

my_fonction()
```

```ruby
def my_fonction
    input_str = gets.chomp
    return input_str
end

def perform
    my_fonction()
    puts input_str
end

perform()
```

```ruby
def my_fonction
    input_str = array.new
    for i in 0..20
        input_str[i] = 20 - i
    return input_str
end

my_fonction() = result
puts result
```

4. **Question 4 (modulo)**
- Qu'est-ce qu'un modulo et à quoi ça peut servir dans un code ?

5. **Question 5 (prototypage et spec)**
- Dans le code suivant, quel est le prototypage de la méthode appelé pour ce test ?

```ruby
describe '#size_compare' do
  it 'it should return a true boolean' do
    expect(size_compare(str_first, str_second)).to eq(true)
  end
end
```

6. **Question 6 (travail avec les chaînes de caractères)**
- Comment inverser une chaîne de caractères en Ruby ?

7. **Question 7 (Manipulation de chaînes de caractères)**
- Comment concaténer (mettre bout à bout) deux chaînes de caractères en Ruby ?

8. **Question 8 (Manipulation de fichiers)**
- Comment dire à un fichier Ruby qu'il a besoin d'un autre fichier pour fonctionner ?
- Comment le faire avec une Gem ?

9. **Question 9 (envoi de variable entre les méthodes)**
- Comment récupérer une variable d'une méthode à une autre (sans variable globale) ?

## Partie "Avancée" :

1. **Question 1 (les hash)**
- Qu'elle est la différence entre un hash et un array ?

2. **Question 2 (Gems)**
- Qu'est-ce qu'une gem Ruby ? comment l'installer dans un projet Ruby ?

3. **Question 3 (conditions ternaires)**
- Quelle est la syntaxe pour une condition ternaire en Ruby ?

4. **Question 4 (mapping)**
- A quoi sert la méthode de classe .map() ? Comment l'appliquer sur des key,value dans un hash ?

5. **Question 5 (Rubocop)**
- Qu'est-ce que Rubocop et à quoi sert-il ?


# RUBY-INTRO-TEST

Une série de test porté sur ruby en 3 catégories de difficultés. Ces tests vous permettrons de voir les acquis que vous avez engrenger durant c'est deux semaines de ruby.
## Partie "Base" :

1. **Question 1 (variable ruby)**
- Comment déclarer une variable ?

2. **Question 2 (type de variable)**
- Qu'elle est là différence entre `i = 2` et `i = "2"` ?

3. **Question 3 (addition)**
- Résoudre l'addition suivante :
```
i = 5
a = 2
```
Combien font `i + 5 * a` ?

4. **Question 4 (incrémentation et décrémentation)**
- Qu'est-ce que l'incrémentation et la décrémentation
- Dans les lignes suivante, lesquels fonctionnent ?
```
1|   i = i + 1 // i = i - 1
2|   i++ // i--
3|   i+1 // i-1
4|   ++i // --i
5|   i.inc // i.dec
6|   i += 1 // i -= 1

```

5. **Question 5 (type de variable)**
- Qu'est-ce qu'un Array ?

6. **Question 6 (boucles)**
- Comment écrire une boucle `while`, `for`, et `each` ?

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

4. **Question 4 (prototypage et spec)**
- Dans le code suivant, qu'elle est le prototypage de la méthode appelé pour ce test ?

```ruby
describe '#size_compare' do
  it 'it should return a true boolean' do
    expect(size_compare(str_first, str_second)).to eq(true)
  end
end
```

## Partie "Avancée" :

1. **Question 1 (les hash)**
- Qu'elle est la différence entre un hash et un array ?

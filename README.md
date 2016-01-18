# RUBY-ON-RAILS-JORNADA-CITI-2016.1

## História

•Criada por Yukihiro “Matz” Matsumotoem 1995

•Misturou partes das suas linguagensfavoritas: Perl, Smalltalk, Eiﬀel, Ada eLisp

•“Ruby é projetada para fazer osprogramadores felizes” (Matz)

## Características

- Interpretada

- Multiplataforma

- Intuitiva

```ruby

2.day.ago

Time.now

3.times

```

- Flexível

```ruby
class
    String
    def letters
        self.gsub(/\d/,"")
        end
    end
    "ru2378by823ro2343ots".letters

    #=> "rubyroots"
```

- Multiparadigma

    - Orientada a Objetos

```ruby
    mandela = Person.new
    gandhi = Person.new
    mandela.say_hello
    mandela.be_friends_with(gandhi)
```

    - Funcional

```ruby
    [1,2,3,4,5].select {|n| n % 2 == 0 }

```

    - Imperativa

```ruby
    numbers= [1, 2, 3, 4, 5]
    even= []
    
    numbers.each do|n|
        even<< n if n.even?
    end
```

    - Reflexiva

```ruby
    beagle.is_a? Animal
    # => true
 
    "A String".methods
 
    # => [:<=>, :==, :===, :eql?, :hash,:casecmp, :+, :*, :%, :[], :[]=, :insert, :length, :size, :bytesize, :empty?, :=~, :match, :succ, :succ!,(...)]

```

- Tipagem Dinâmica Forte

```ruby
name= "Nelson Mandela"
 age= 94
 name+ age
 
# => TypeError: can't convert Fixnum into String
```

- Tudo é objeto

```ruby
    3.times
    # => #<Enumerator: 3:times>
    
    'im an object'.emtpy?
    
    # => false
```



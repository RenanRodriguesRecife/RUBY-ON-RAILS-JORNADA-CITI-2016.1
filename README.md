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
    
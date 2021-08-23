# Commons Entity

Lib criada para abstrair a logica de criação de entities para persitencia.

### Utilização

Adicione a depedencia no pom do projeto

``` xml
<dependency>
    <groupId>br.com.macorin.libs</groupId>
    <artifactId>commons-entity</artifactId>
    <version>${commons-entity.version}</version>
</dependency>
```

Na tua entity, extenda o `BaseEntity`. Teu objeto persistido terá já o um ID, uma data de criação preenchida no momento da primeira persistencia em banco e uma data de alteração, tambem alterada de acordo com a ultima persistencia em banco.
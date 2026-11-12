# CONTROLLER
```
@RestController
```
# POST
```
@PostMapping
```

# PARÂMETRO BODY
```
public tipo funcao(@RequestBody tipo valor){}
```

# PARÂMETRO VARIÁVEL
```
@GetMapping("{id}")
public tipo funcao(@PathVariable tipo valor) {}
```

# PUT
```
@PutMapping("{id}")
public tipo funcao(@PathVariable tipo valor, @RequestBody tipo entidade) {
...
repository.save(entidade);
}
```

# QUERY PARAMS

```
public List<Tipo> buscar(@RequestParam("nome") String nome, @RequestParam("outro") Tipo outro)
```
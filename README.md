## laravel shortcuts

```
php artisan make:model Post -mc

```

### debug eleqouent query

```
        $query = self::where('id','=',$id);
        $query->toSql();
        dd($query->getBindings());
```

# useForm Hook 

Ejemplo:

```
    const inialForm = {
        name: '',
        age: 0,
        email: ''
    };

    const [ formValues, handleInputChange, reset ] = useForm( initialForm );
```
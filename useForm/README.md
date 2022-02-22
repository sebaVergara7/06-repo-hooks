# useForm Hook


Ejemplo de uso:
```
    const initialForm = {
        name: '',
        ager: 0,
        email: ''
    };

    const [ formValues, handleInputChange, reset ] = useForm(initialForm);
```
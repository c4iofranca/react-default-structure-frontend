# Components

All the main components of each screen. All secondary components present in features folder will be pulled from them. 

# Guide
index.tsx
```
/**
* import area
*/
import ... from '...'

/**
* @returns Component.
*/
const Component = () => {
    /**
    * Define states
    */
    const [state, setState] = useState();

    /**
    * Request functions or Aux Render Functions
    */
    const doThis = async () => {
        try {
            ...
        } catch {
            ...
        } finally {
            ...
        }
    }

    const renderThis = () => {
        return (...)
    }

    // Lifecycle Effect
    useEffect(() => {
        doThis();
    }, [])

    // Component return 
    return (
        ...
    )
}

export default Component;
```
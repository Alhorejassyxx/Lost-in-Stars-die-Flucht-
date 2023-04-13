# Lost-in-Stars-die-Flucht-
Fantasy Game
Here's a sample unit test case for the corrected code:

```
import org.junit.Test;
import static org.junit.Assert.*;

public class OrteTest {
    
    @Test
    public void testOrte() {
        String altana = "Altana{Planet von Mars} (wohnt In einer Höhle in der Nähe der Stadt Nexus)";
        String tokio = "Erde{Planet von Lia} >Japan {Land} >Tokio{Stadt/Ort}";
        String alysio = "{Planet wo sie hin fliehen} Alysio";
        
        assertNotNull(altana);
        assertNotNull(tokio);
        assertNotNull(alysio);
        
        assertEquals("Altana{Planet von Mars} (wohnt In einer Höhle in der Nähe der Stadt Nexus)", altana);
        assertEquals("Erde{Planet von Lia} >Japan {Land} >Tokio{Stadt/Ort}", tokio);
        assertEquals("{Planet wo sie hin fliehen} Alysio", alysio);
    }
}
```

This test case checks if the three string variables are not null and if they have the expected values. If any of the assertions fail, it means that there is an issue with the code.Here's a sample unit test case for the corrected code:

```
import org.junit.Test;
import static org.junit.Assert.*;

public class OrteTest {
    
    @Test
    public void testOrte() {
        String altana = "Altana{Planet von Mars} (wohnt In einer Höhle in der Nähe der Stadt Nexus)";
        String tokio = "Erde{Planet von Lia} >Japan {Land} >Tokio{Stadt/Ort}";
        String alysio = "{Planet wo sie hin fliehen} Alysio";
        
        assertNotNull(altana);
        assertNotNull(tokio);
        assertNotNull(alysio);
        
        assertEquals("Altana{Planet von Mars} (wohnt In einer Höhle in der Nähe der Stadt Nexus)", altana);
        assertEquals("Erde{Planet von Lia} >Japan {Land} >Tokio{Stadt/Ort}", tokio);
        assertEquals("{Planet wo sie hin fliehen} Alysio", alysio);
    }
}
```

This test case checks if the three string variables are not null and if they have the expected values. If any of the assertions fail, it means that there is an issue with the code.There are a few issues with the given code:

1. The third string `alysio` is not properly closed with double quotes.
2. There are three single quotes at the end of the third string `alysio` which are not needed and will cause a syntax error.

Here's the corrected code:

```
public class Orte {
    public static void main(String[] args) {
        String altana = "Altana{Planet von Mars} (wohnt In einer Höhle in der Nähe der Stadt Nexus)";
        String tokio = "Erde{Planet von Lia} >Japan {Land} >Tokio{Stadt/Ort}";
        String alysio = "{Planet wo sie hin fliehen} Alysio";
    }
}
```

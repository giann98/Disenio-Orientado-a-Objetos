# MyGymFitnessPro - Diseño del sistema #

**Apellido**: Pasquali <br>
**Nombre**: Gian Franco Martin <br>
**Profesor**: Matias Velasquez <br>
**Año**: 2024 <br>

## Introducción ##
Bienvenidos, este es el diseño de una aplicación para un gimnasio, la cual fue solicitada por el gimnasio FitnessPro. 
La gestión es llevada a cabo de manera manual, lo que le imposibilita ofrecer un 
servicio más personalizado y de atender de una manera ágil a sus clientes. <br>

El cliente nos planteó su manera de trabajar, en base a esto pudimos concluir que los requisitos indispensables que debe tener nuestra aplicación son los siguientes: <br>

+ **Registro de Socios** <br>
+ **Gestión de Reservas y de Clases** <br>
+ **Control de Acceso** <br>

Por otra parte, también se encontraron los siguientes requisitos que son importantes para la gestión: <br>

+ **Registro de Usos de Equipos** <br>
+ **Interacción con los Socios** <br>

En el siguiente link se pueden observar las entidades que se identificaron y las tarjetas CRC realizadas [Entidades y Tarjetas CRC](https://excalidraw.com/#json=PAbuZGyZqASr6KPmWYuO4,jNbcVH_AbMf0Wef2ZpP1ng) <br>


## Diagramas y Diseños ##
En esta sección se puede observar el diagrama de casos de uso realizado [Diagrama Casos de Uso](https://drive.google.com/file/d/1zPBe_UbrtpQ5K9Bl5MD2U1gazO3tEHQd/view), en caso de no poder visualizar, acceder haciendo click aqui [Diagrama Casos de Uso - Draw](https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Copia%20de%20Diagrama%20Casos%20de%20Uso%20(DOO).drawio#R%3Cmxfile%3E%3Cdiagram%20name%3D%22P%C3%A1gina-1%22%20id%3D%222rNKyTdJx1m8RtrSMfy1%22%3E7V1bc5s4GP01fmwGIS7mMXHSJNN2N9PMdtu%2B7BBQbG0xcoWcy%2F76FTcb6yM2wSBIpy8tyFguh3O%2Bq0QneLZ8uuT%2BavGJhSSamEb4NMHnE9NEhm3Iv9KR53zEnHp2PjLnNCyu2g7c0v9I%2BdVidE1DkuxcKBiLBF3tDgYsjkkgdsZ8ztnj7mX3LNr91ZU%2FJ2DgNvAjOPo3DcUiH52a7nb8itD5ovxl5Hj5J0u%2FvLi4k2Thh%2ByxMoQvJnjGGRP50fJpRqIUvRKX%2FHvvX%2Fh08w%2FjJBZNvhBe3%2F7888a7ePh49WFtzbz1x2T1ziyexoMfrYs7nphOJCc8u5MH8%2FTgliaCLH151SVdxn5CmTx8T0VMkuSGs%2FJ6%2BcubrxR3LJ5LGDlbxyFJ%2FyWG%2FPhxQQW5XflB%2BumjZI4cW4hlJM%2FQ5tvVOytu9oFwQZ4qQ8WdXhK2JII%2Fy0uKT6cF6AXt3pkYF3f6uH2KjufkY4vKE5xaxVf9gjnzzeRbcOVBge8rsEYmwPozmUtwuc%2FlcLwmDymyCQsyhEmcnpTYK3jKn5MKIFqwRBYA0zAAmJurqmC6vWEJoDwNlzTOwAwZB3hJ8a3Sw%2FUyOg2EvACfpQBQKfSP%2Fh2JblhCBWWxvOSOCcGWlQtOIzpPPxBMwZatRURjMtuYHqMbwLGKN5pCvHEN3E5vcEO8ISXj8DQ1uPIsZjHZhWpX%2F%2BSJiq%2Fp8YldnH3bOTt%2Fqlx4%2Flw5uSGcylsi%2FBDaCVvzgBxmkPD5nIgGqiXhjqOAD6%2FybOyaZ1OOcRL5gj7supe6B1b8wg2j8tY23Ni4k4IcHlaeeX7jxbeq7kCdyN2dyFUnypEBE2X82dx2e0qZHqDUbW753rJ0XU%2FVrmENrF0M3Y6M0%2Bi9xCd1O6EvWJL%2BnUVuSe0j0OltTENFcAPXYN4GYwDhRUSlvxkpgpbqP2o4qBlBa6QORMLMn79WTyozpafbqbKzcq7%2BHU%2Bp25E4HmDYkBooN%2FU82IRTWVp9D67Len6zcS8b8ajY6Nr9sdFwbL1sdAAbr%2BMgWj%2BTfaRkK5kgpjwoiyYyUMVnoZ8sMl6iJoRFr6GrfmqaTbnpNuRm8cjfGSeGUaY0VZfodENOy3ZOHJWfZkt%2BWpZ34nm2M8WWjU3sYpX5pt2MrtuZywvZ%2FX1C%2BqG0WxMwkTlNwyVBV2l5Y0mWd5wkdNjaBrZV9WM0eKw0BeDd%2BPMs1MwiTAigHJfghsOGnbYzQihhkjlC09reRJY6O2wip%2BMykRiGk67b0kACBz5Gi1jSvsLESxKTvPQbcBKSOKB%2BOs0D5WKdHo1Ky8gbWssWrEFq0vJuXI8ahknbyOjbTmDUdZhUSvugDSif1lhsACQZEG5TG%2BBgpE6l1tPGYANgGWnG4mQdiVHWkbAF6kjDG4GO60gtk5q31MCwRpa5A89it8yMEJzK1Zu5WzBzr3Z0%2F0rYRs7k5zoL2wfUMwK5juEMrmeYKP7W8wE9O6PSMyBVaz1L6qn89DTruSbz5uyeJG99RYGaIiHHhcrX2pW0YT50mkhUfC6toWms47SsEUR%2BUhPd67SZSEVuauKBbaY91sUY%2BkvEVtPcx26a%2B2gymp21LxBIogyk12jaJqDjTlZDkxWL6R2NaOiHWTw0CmVjED0anje0smGCODJlI13KLpcHHVa2%2FVvZfSlby6KNX4mMjcvsesjoADK2XS0Ic23D0ExGuGbjM0kIf8i8zFjiRRv2NQZfK23DKsXFk6BSuf1XztssMNAm65JSh32M%2BXpZ99cpM1SmNBWxDQtA6lTdifjHZ%2Fv7wl%2Fc%2F%2FvB%2Ben8%2BGGc%2FTE%2Fr1m2fx3POUkyDWfdr%2Fl2i0nA0h0Q1d7YccIGKq5hzcvCdpUOA%2FJsjcKuRRMG3j24Z%2B3RoiKy7jz2y4wcyj9PkeqgDdRS2y7YpGPg3hx0LZIwd%2FnipzlfKu3TlUgV%2FWkyw5NTL6TB0ZXwo8QMbCpya3bY6BXzYIsAW%2FnoVt3t1yp7nws5KOzpXgb03ttW42XkqaXUxr1tVdlwKr297Vq4YR9nAPo2XJqBRk5dPCh1HXUDDtpsanp1wAmnahhw6qQubPpsHVfeu02EH%2BatXPlHlGaana1e7diPTT2N3YlaNOGKy%2BpuswzPBeM%2Bp7uAdpK6HwWmCVo9ns7Uvd5iwC6ZttT9NVW6oxo%2FnQT8ZUR%2B0Lh6gxpXsI1KKrZ1uxxMpZaaR2Bca3aOz%2Fw4kCim5qDDst1R2kegQe7qXLtej9zo0%2Fvh1F7X991Dv7E0g5DXNr0H7%2BCQU%2BlN7xHM729lmMQn5Qo3ULnL%2Ffo4yncONJY6177VIzr6PdFvoX73QrL09gp46ltfkGdqVvivuSu6Ez42Td2ROyZ%2F037xgda1mPVI7l9bvfRjQWK6lLlQVlruZn31cdm46mO2xmA4HwPrctXFWWp5o7uV6h2H497g9XkEy0S6UnF92%2FS7KXPWbErdI%2FHhcnF1gRVy1f0jbV%2BmJdlSLgUaJhe3nS%2Fmo%2F31v8fzf9ZXnnl9f7X8XtN9r6TiWbTO8xU1k3FV5mzwNkejjA91mINaLDtOzltG3F3vW%2Bktdn%2BZj4OF7uA9Y0bbV3TU9N4b7kDvStkwNz8NApIM%2FzK9o3TvqrpHrgHf4trXtpVaoN9Wyo56cfr7GNi2Lf%2F20nUQPEz7K8jVIj7WbH0AUg1bAzLUKq9rtCSVXUa726lsTyupYNI9DlLpLUk2JWPtdYNWgHomY2%2BrhV9GUl3xLziN8xeJ%2BUWIk%2Bcqnbwv47g0BfRonB7flyFPt%2F93QI749r9gwBf%2FAw%3D%3D%3C%2Fdiagram%3E%3C%2Fmxfile%3E).<br>


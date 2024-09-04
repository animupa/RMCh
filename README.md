# RMCh
Dataset of the Chilean Musical Review's (_Revista Musical Chilena_) Chilean Musical Creation (_Creación Musical Chilena_) section (2012 - 2022).

It consists of 4841 entries (one per performance) and 16 variables :
- 'ID': unique identifier of the performance (produced by Animupa)
- 'Año': year of the performance
- 'Título y Medio': description of the performance and main instrument played
- 'Ocasión y Lugar': event and place where the performance took place
- '# representaciones': number of shows
- 'Última representación': date of the last performance
- 'GP compositor': presumed gender of the compositor
- 'Título': title of the performance (identified by algorithm)
- 'Medio': main instrument played (identified by algorithm)
- 'Ocasión': event to which the performance was attached (identified by algorithm) 
- 'Lugar': place where the performance took place (identified by algorithm)
- 'Facebook live': whether the performance took place through Facebook Live (mostly during the 2020-2021 pandemics)
- 'Universidad de Chile': whether the performance took place in the premises of the University of Chile (the editor of the Chronics)
- '# Intérpretes GP H': number of musicians that are presumed to be male (identified by algorithm)
- '# Intérpretes GP M': number of musicians that are presumed to be female (identified by algorithm)
- '# Intérpretes GP ND': number of other musicians which gender could not be guessed (identified by algorithm)

#### NB: When identified through algorithms, the data is likely to contain errors due to inconsistant structure of the raw data

## Source

All data has been retrieved from the digital version of the Musical Chronics edited by the Chilean Musical Review (Revista Musical Chilena).

## Licence

This dataset and associated code in the repository are distributed under the CC BY-NC 4.0 license.

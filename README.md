# q2eVenues


### Install Laravel
```laravel
 install Laravel 8
```

# ich habe die Tablen gemachet

#### *Venues* 
#### *Event_types* 
#### *Locations* 


# Verbine die Table miteinander

#### *Venues* mit   *Locations*  > One to Many


#### *Venues* mit   *Event_types*  > Many to Many
Sollen wir Pivot table machen > event_type_venue


# Ich habe index oder homepage eingestellt

### Routing nach Index 
### ein Controller frontHomeController gemacht >> in controller ftech in view nach --> q2e.index
### In Index.blade  print :
ich have ein template verwendet
  ***$featuredVenues***   --> Dass es ist resviert 
  ***$eventTypes***   --> Dass es ist Ereignistypen   so wie eins Hotel oder feirenwhong etc .
  ***$newsetVenues***   --> Dass es ist Veranstaltungsorte 
  
  ***


  
 # Routing nach Venues/{slug}/{id} 
### ein Controller VenueController gemacht >> in controller ftech in view nach --> q2e.venue
### kann man die details Veranstaltungsort  sehen
### In venue.blade  print :
ich have ein template verwendet
  ***$venue***   --> Dass es ist details  Veranstaltungsort so wie name , phone , peice , wie vil person oder die adresse 
  ***$relatedVenues***   --> Dass es ist verwandte Veranstaltungsorte   .
  
   ***

# Routing nach event_type/{slug} 
### ein Controller EventTypeController gemacht >> in controller ftech in view nach --> q2e.event_type
### kann man die details Event_type  sehen
### In event_type.blade  print :
ich have ein template verwendet
  ***$eventType***   --> Dass es ist details  EventType  
  ***$venues***   --> Dass es ist relationship  Veranstaltungsorte  mit EventType .
    ***

  
# Routing nach location/{slug} 
### ein Controller LocationTypeController gemacht >> in controller ftech in view nach --> q2e.location
### kann man die details Location  sehen
### In location.blade  print :
ich have ein template verwendet
  ***$location***   --> Dass es ist details  oder ftch Location  
  ***$venues***   --> Dass es ist relationship  Veranstaltungsorte  mit Location .
    ***

    
# Routing nach search
### ein Controller SearchController gemacht >> in controller ftech in view nach --> q2e.search
### Er kann finden , was er sucht , so wie Venue , Location , Personen
### In search.blade  print :
ich have ein template verwendet
  ***$venues***   --> Dass es ist details   search
   ***

  
  #Routing nach search
### ein Controller SearchController gemacht >> in controller ftech in view nach --> q2e.search
### Er kann finden , was er sucht , so wie Venue , Location , Personen
### In search.blade  print :
ich have ein template verwendet
  ***$venues***   --> Dass es ist details   search
  
  ***
  
   # Ich habe die Seeder für all die Tablen gemacht 
   

 
 
   
   
   
  
  



  
  
  
  
  








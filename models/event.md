## Relationships

### EventResponseType

```php
const GROUP_NAME_GLOBAL = 'global';
const GROUP_NAME_WORKSPACE = 'workspace';
const GROUP_NAME_EVENT_TYPE = 'event_type';
const GROUP_NAME_EVENT = 'event';

// We auto generate event response types for so-called responsible users (users who have a responsability on an event)
// This auto generation takes the name of a PersonType. To flag/mark this, we use a prefix in the name
const PERSON_TYPE_EVENT_RESPONSE_PREFIX = 'RESPONSABILITY:';
```

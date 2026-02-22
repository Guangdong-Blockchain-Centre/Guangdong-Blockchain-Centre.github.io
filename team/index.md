{% include section.html %}
{% include list.html data="members" component="portrait"
  filter="role == 'principal-investigator'"
  group_by_year="false" sort="order" %}

{% include list.html data="members" component="portrait"
  filter="role != 'principal-investigator'"
  group_by_year="false" sort="order" %}

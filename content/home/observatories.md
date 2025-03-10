---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 25

title: Automated Data Observatories
subtitle: From open data and open-source statistical software to data-as-service.

content:
  # Page type to display. E.g. project.
  page_type: observatories

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
  - name: All
    tag: '*'
  - name: Music
    tag: music
  - name: Competition
    tag: competition
  - name: Cultural Creative Sectors Industries
    tag: ccsi
  - name: Green Deal
    tag: climate-change
  - name: Economy
    tag: economy

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 5

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="text-align: center;">{{< figure src="/media/icons/dmo_avatar.png" caption="[Digital](/observatories/music/)</br>[Music Observatory](/observatories/music/)</br>Our first observatory, with seven years of data sharing history, a model for the European Music Observatory." numbered="false" >}}</td>
<td style="text-align: center;">{{< figure src="/media/icons/cdo_avatar.png" caption="[Competition Data Observatory](/observatories/competition/)</br>Our youngest, early-stage prototype observatory for computation antitrust." numbered="false" >}}</td>
<td style="text-align: center;">{{< figure src="/media/icons/gdo_avatar.png" caption="[Green Deal Data Observatory](/observatories/greendeal/)</br>An ambitious project to connect environmental sensory data, political and policy survey data with socio-economic indicators." numbered="false" >}}</td>
<td style="text-align: center;">{{< figure src="/media/icons/edo_avatar.png" caption="[Economy Data Observatory](/observatories/economy/)</br>An incubator for socio-economic data observatories. Its first offspring is the Competition Data Observatory." numbered="false" >}}</td>
</tr>
</tbody>
</table>



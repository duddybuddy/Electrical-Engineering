## Schematic Checklist

## PCB Checklist

## Release Package Checklist

## Symbol Creation Checklist

## Footprint Creation Checklist

## PCB Tips
### Scripting Console One Liners
#### Change all Fab Layer "Value" texts to be hidden 
```import pcbnew; board = pcbnew.GetBoard(); [f.Value().SetVisible(False) for f in board.GetFootprints()]; pcbnew.Refresh()```

#### Select all traces of a given width
```import pcbnew; board = pcbnew.GetBoard(); target = pcbnew.FromMils(12); [t.SetSelected() for t in board.GetTracks() if t.GetWidth() == target]; pcbnew.Refresh()```

PUML=/usr/bin/plantuml
ALL=dcp_presentation_flow.png


all: $(ALL)

%.png: %.puml
	$(PUML) $<

clean:
	rm $(ALL:.puml=.png)
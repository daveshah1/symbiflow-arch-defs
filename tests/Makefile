
SUBDIRS=$(sort $(wildcard [0-9]-*))
ARCHS=$(sort $(basename $(notdir $(wildcard make/arch/*.mk))))

list:
	@echo "Tests are:"
	@for D in $(SUBDIRS); do echo "   $$D"; done
	@echo ""
	@echo "Architectures are:"
	@for A in $(ARCHS); do echo "   $$A"; done
	@echo ""

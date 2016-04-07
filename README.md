# Ti.Calendar

A simple calendar widget for Titanium Alloy.



_.defaults(args, {

	// Data
	current_date: Moment(),
	active_dates: [],
	min_date: Moment().subtract(6, 'months'),
	max_date: Moment().add(6, 'months'),

	// Style
	backgroundColor: 'transparent',
	dateBackgroundColor: 'transparent',
	todayBackgroundColor: '#af80',
	dateTextColor: '#fff',
	todayTextColor: '#000',
	activePinColor: '#f39911',
	inactivePinColor: 'transparent',
	selectedBackgroundColor: '#60f39911',
	fontFamily: '',

	// Behaviour
	allowInactiveSelection: false,
	fillMonth: false,
	enablePastDays: false

});

# DT5724-ReadOut
Command-line tool for acquiring data with the CAEN DT5724 digitiser.

The code is based on the examples provided by CAEN, with changes made to permit automated measurements.

The present version is preliminary and is hard coded to acquire data on inputs 1, 2 and 3 (not 4) with hardwired trapezoidal filter settings.

Two arguments are expected, the duration of the measurement in seconds and the prefix of the filenames.

Example usage via ssh

ssh -t del@delnote8.del.frm2 '~/CAEN/DT5724-ReadOut/bin/DT5724RO 20 test'

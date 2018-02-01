% Binarise the image with Threshold = 128

%This could be directly done as
% load 'l256.dat';
% a = importdata('l256.dat');
% b = a>128;
% imshow(b)

% Alternate method

load 'l256.dat';
A = importdata('l256.dat');
n = size(A);
imshow(A, [0, 255]);
B = zeros(n);
for m = 1:n
    for n = 1:n
        if A(m,n) > 128
            B(m,n) = 1;
        else
            B(m,n) = 0;
        end
    end
end
disp(B);
figure,imshow(B, [0, 1]);

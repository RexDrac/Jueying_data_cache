gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
max-step-num: 2500000000
train-step-num: 1
critic-lr: 0.0003
gating-activation-fn: ['relu', 'relu', 'None']
max-path-num: 20
critic-layer-size: [256, 256]
max-episode-num: 5000000
actor-l2-reg: 0.0003
task-weight: 0.2
test-num: 4
state-dim: 25
actor-activation-fn: ['relu', 'relu', 'None']
rollout-step-num: 1
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
max-train-time: 10
interpolation: False
loss-output-bound-coeff: 0.0
HLC-frequency: 25
max-path-step: 5000
actor-layer-size: [256, 256]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-entropy-coeff: 0.0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
replay-buffer-size: 1000000
critic-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
env-id: HumanoidBalanceFilter-v0
goal-weight: 0.4
loss-output-smooth-coeff: 2.0
imitation-weight: 0.4
prioritized-exp-replay: True
epoch-num: 500
critic-l2-reg: 0.0003
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
squash-action: True
n-step: 1
gating-layer-size: [128, 128]
action-dim: 12
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
LLC-frequency: 500
render-eval: False
reward-scale: 0.1
dsr-gait-freq: 1.667
record-start-size: 10000.0
Physics-frequency: 1000
actor-lr: 0.0003
filter-action: True
replay-ratio: 1
expert-num: 8
tau: 0.001
replay-start-size: 10000
joint-interpolation: True
batch-size: 128
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
action-bounds: [[-0.39  -2.79   0.66  -0.39  -2.79   0.66  -0.39  -1.884  0.66  -0.39
  -1.884  0.66 ]
 [ 0.39   0.348  2.73   0.39   0.348  2.73   0.39   0.348  2.73   0.39
   0.348  2.73 ]]
loss-output-diff-coeff: 0
total-step-num: 2500000000
max-test-time: 10
filter-torque: False
gamma: 0.986
dsr-gait-period: 0.6
actor-weight-decay: 1e-06
critic-weight-decay: 1e-06
epoch-step-num: 5000000
